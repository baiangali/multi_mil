# multi_mil
Annotated Corpus: Information Operations in Military Discourse
This dataset contains labeled using Label Studio as part of a research project on detecting and classifying information operations (IO) in military and geopolitical discourse.

Annotation Schema
Each text is annotated with:

Named Entities (NER-style span annotations):

MIL_TERM — Military terminology

TARGET_AUDIENCE — Target audience of the message

SOURCE — Source or author of the information

GEO_LOC — Geographic references

TIME_REF — Temporal references

AUTHOR_INTENT — Implied intent of the author

TARGET_ENTITY — Intended object of influence or attack

Document-level classification labels:

IO_TYPE: Type of information operation
(DISINFORMATION, DEMORALIZATION, DISCREDITATION, INTIMIDATION, HATE_INCITEMENT, PANIC_CREATION, PROVOCATION, AUTHORITY_UNDERSCORE)

EMO_EVAL: Emotional tone
(Позитивная, Негативная, Нейтральная)

FAKE_CLAIM: Presence of false claims (True, False)

Format: JSON file exported from Label Studio (compatible with NLP training pipelines)


Use Cases
This corpus can be used for:

Training and fine-tuning transformer-based models (BERT, RoBERTa)

Developing information operation detection systems

Building military-domain ontologies

Multilabel classification and NER in Russian

Emotion and deception detection in geopolitical media content
