# IFoodCaseLeonardo202511
Case apresentado como requisito do processo seletivo.

Essa pasta conta com arquivos auxiliares que complementam a entrega pincipal do case. 
O arquivo .pdf é a apresentação central é a partir dele que a narrativa acontece.
O arquivo.jpg é o diagrama técnico das Fatos e Dimensões
O arquivo .pbix é o que utilizaei para desenvolver o dashboard Power BI
O arquivo .ipynb é o notebook e foi desenvolvido utilizando o Databricks Community
  -notebook: 

Para rodar o notebook, por favor siga as intruções a seguir:

notebook: etl_modelagem_case_ifood.ipynb

-Executa o notebook até o bloco 'PARAMETROS'
-renomeie os arquivos csv, incluindo sufixos de data no nome seguindo esse padrão:
"nome_da_base_AAAAMMDD_HHmm"

Por exemplo:
cluster_merchant_history_20251101_0923
merchant_info_20251101_0923
conversion_base_20251101_0923
communications_base_20251101_0923

e inclua cada tabela na sua pasta correspondente:/
Ex:
/Volumes/workspace/ifood_bronze/origens/communications_base/  --> communications_base_20251101_0923
/Volumes/workspace/ifood_bronze/origens/merchant_info/ --> merchant_info_20251101_0923
/Volumes/workspace/ifood_bronze/origens/conversion_base/ --> conversion_base_20251101_0923
/Volumes/workspace/ifood_bronze/origens/communications_base/ --> communications_base_20251101_0923

Após esse processo, o restante dos blocos deve ser executado até o final.
