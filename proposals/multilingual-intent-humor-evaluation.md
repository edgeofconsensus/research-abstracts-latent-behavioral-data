# Multilingual humor and communicative-intent evaluation
Status: proposal; not an OpenAI fine-tuning job.

## Problem
Speech and text models may confuse jokes, irony, quotations, metaphors and literal technical requests, especially in Ukrainian/English/Russian code-switching, dialectal pronunciation and casual speech.

## Evaluation protocol
Collect only consented or synthetic examples, with context, intended interpretation, ambiguity labels and annotator disagreement. Compare text-only, ASR-transcribed and audio-context interpretations where consent and tools permit. Evaluate calibration, false literalization, false humor attribution, language switching and error recovery. Preserve ambiguity rather than assigning unsupported certainty.

## Governance
Remove identifying information, avoid inferring personal identity from humor, version the dataset, maintain held-out evaluation splits and document annotation policy. Fine-tuning a provider model requires a separately supported training workflow; writing this proposal or a checkpoint does not change model weights.
