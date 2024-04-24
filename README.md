# llamaid_configs

**App_commands**

Based on your requirement you can edit the yaml file and deploy the securechat

**llm_app_command**: d3x apps create –config  sec_llm_summ.yaml

**openai_app_command**: d3x apps create –config  sec_openai_summ.yaml


**Ingestion**

**Openai_Ingestion:** d3x dataset ingest -d <dataset_name> --config openai_ingest.yaml

**hugging_Ingestion:** d3x dataset ingest -d <dataset_name> --config hugging_ingest.yaml

**question mode**  d3x dataset query --dataset <dataset_name> --config <openai_summ_hugging_emb_rag.yaml> --question

**batch mode** d3x dataset query --dataset <dataset_name> --config <openai_summ_hugging_emb_rag.yaml> -b<absolute_path_of_json>.

**interactive**d3x dataset query --dataset <dataset_name> --config <openai_summ_hugging_emb_rag.yaml> -i.


