# Desafio-BigData-AWS-DIO

## Job Contador de Palavras processado em ambiente Big Data (Hadoop) Gerenciado pela AWS.

1. O arquivo sherlock.txt(/Arquivo-Entrada) foi alvo do job que realizou a contagem das palavras do referido.
2. O processamento foi feito na estrutura de máquinas virtuais (ECR) com processamento Big Data (EMR), tudo armazenado em Bucket S3.
3. As tasks foram disparadas pelo código python (/CodigoPython) que leu o arquivo de entrada, contabilizou as palavras e armazenou em arquivos de log(/Log-saida).

