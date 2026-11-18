Supplementary material for SSA-Inspector
========================================

Decision rules, segmentation settings, prompts and response schemas

This repository specifies the rules and model inputs used by SSA-Inspector for
photograph-based screening of masonry buildings. It covers the evaluated configuration,
in which no coordinates, building identifiers, inspector notes or any other building
attributes were supplied. Predictions describe visible condition and support preliminary
screening; they do not certify occupancy or establish earthquake causation.

Contents
--------

S1_photograph_classification_rules.txt
    S1 Photograph classification rules
S2_building_synthesis_and_response_validation.txt
    S2 Building synthesis and response validation
S3_segmentation_and_model_settings.txt
    S3 Segmentation and model settings
S4_system_prompts.txt
    S4 Full system prompts
S5_response_schemas.txt
    S5 Full response schemas
prompts/agent2_visual_assessment.txt
    S4a Agent 2 system prompt
prompts/agent3_building_assessment.txt
    S4b Agent 3 system prompt
schemas/agent2_response.schema.json
    S5a Agent 2 response schema
schemas/agent3_response.schema.json
    S5b Agent 3 base response schema
