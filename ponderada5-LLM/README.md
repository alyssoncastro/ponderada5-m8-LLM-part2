# Construção de um chatbot com LLM e RAG

#### Autor: Alysson C. C. Cordeiro.

##### ENGENHARIA DA COMPUTAÇÃO - MÓDULO 8.
###### Instituto de Tecnologia e Liderança (INTELI)

---

### ESCOPO GERAL DO CHAT:

Um chatbot beseado em LLM usando a API do ChatGPT, o qual foi desenvolvido para apenas responder sobre regras e normas da segurança do trabalho, além de utensílios e peças para manutenções. Mas agora com código simples e básico de RAG, que é um modelo que utiliza uma estrutura de indexação para recuperar e fornecer informações relevantes a partir de uma fonte externa, o que pode ser um documento ou uma base de dados. Com isso, o RAG da OpenAI é um modelo que foi projetado para recuperar documentos relevantes para uma determinada consulta ou pergunta. 

### QUAIS FORAM AS TECNOLOGIAS?


    1. Python 3.11
    2. OpenAI
    3. Gradio (Quickstart)
    4. Miniconda
    5. Langchain
    6. DotenV
    7. RAG e LLM
    8. ChatPDF (para teste)

### QUAIS AS FUNCIONALIDADES?

O chatbot está primeiramente com layout estilo de conversa de bots para o usuário ter uma experiência melhor. No campo "type a messager", o usuário digita uma saudação "oi!", "bom dia", entre outros.E existem 3 botões abaixo do campo: um para retrair, outro para pagar texto do campo digitado e outro para limpar as conversas.

Ao enviar a mensagem, o usuário recebe em aproximadamente 5 segundos, uma resposta correspondente a que ele perguntou, que seria sobre segurança do trabalho. Caso contrário, será mostrado como resposta que é só possível responder se o assunto for relacionado ao ambiente de trabalho ou sistemas de manutenções.

A grande diferença da 1° parte para a 2° parte da atividade é que foi usado um sistema que foi capaz de contextualizar as respostas de um documento.

##### DOCUMENTO AQUI EM TXT:

[Workshop rules and safety considerations](documento.txt)

o documento foi tirado do site:

[clique no aqui](https://www.deakin.edu.au/students/study-support/faculties/sebe/abe/workshop/rules-safety)

    OBS: foi usado txt pelo fato da biblioteca PyPDFs não rodava, devido à incompatibilidade de versões. Logo, era permitido, segundo o requisito arquivos. Vale lembrar que você pode estar realizando essa construção de várias formas para cada formato de arquivo ou documento.

### COMO DEVO INSTALAR?

1. CLONE O MEU REPOSITÓRIO:

```python
git clone https://github.com/alyssoncastro/ponderada5-m8-LLM-part2.git

cd ponderada5-LLM
```

2. DEPENDÊNCIAS:

```python
python3 -m venv llm
source llm/bin/activate
```

3. EXECUTANDO:

```Python
python3 interface.py
```

4. VÍDEO:
   
[CLIQUE PARA ASSISTIR](https://drive.google.com/file/d/1-JLRi--Tb4rrAkp4vXkKC3InLJ87Ih0E/view?usp=drivesdk)
---
## NOTA

Sem esqeucer de agradecer ao professor Nicola pela paciencia de esperar essa atividade, na qual cumpri majoritariamente sozinho. Dando sempre feedback. E agradecê-lo pela compreensão do meu esforço. Mesmo projetinho ponderado não saindo perfeito.

    


