# AI Automation Flow

## AI Responsibilities

The AI layer is responsible for processing
unstructured complaint emails.

Main tasks:
- extracting order numbers,
- language detection,
- complaint summarization,
- defect categorization.

## Confidence Score

Each AI classification returns a confidence score.

Example:
- Material defect -> 0.93 confidence

Low confidence cases are redirected
to manual review.

## Human-in-the-loop

Final business decisions should remain under human supervision.

AI supports specialists but does not fully replace them.

## Edge Cases

### Missing Order Number
Customer receives automatic clarification request.

### Low Confidence Classification
Complaint is routed to manual verification.

### SAP Unavailable
Retry mechanism and processing queue are used.

### Duplicate Complaint
Similarity detection can identify repeated issues.

## Proposed AI Stack

- Azure OpenAI
- Prompt-based extraction
- Classification with confidence scoring