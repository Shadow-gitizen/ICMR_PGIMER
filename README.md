# Medical Prescription Information Extraction with Phi-4 Multimodal Model

Extract structured medical information from handwritten prescriptions using Microsoft's Phi-4 multimodal AI model. Converts unstructured prescription images into machine-readable JSON/CSV format.

## Features
- **Field Extraction**: Doctor details, patient info, medications, dosage, frequency
- **Multimodal Processing**: Handles both text and image data
- **Structured Output**: Generates JSON and CSV formats
- **Batch Processing**: Processes entire directories of images

## Evaluation

To assess the prescription extraction system's performance,we can implement these evaluation steps:

**Key Metrics**
| Metric       | Description                                  | Target Range |
|--------------|----------------------------------------------|--------------|
| Field F1     | Per-field accuracy (exact match)             | >0.85        |
| Token Recall | Percentage of correct medication tokens      | >90%         |
| Schema Validity | Valid JSON output rate                     | 100%         |

**Implementation Steps**
1. Prepare gold standard dataset with annotated prescriptions (Takes a lot of time)
2. Run extraction on test images:
