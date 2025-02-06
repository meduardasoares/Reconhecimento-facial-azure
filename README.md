# 🚀 Reconhecimento Facial no Azure com o Estúdio de Visão  

Este projeto utiliza o **Estúdio de Visão da Azure (Azure Vision Studio)** para realizar **reconhecimento facial** em imagens.  

## 📌 Objetivo  
Explorar as capacidades do **Azure Vision Studio** para detectar rostos em imagens e analisar suas funcionalidades.  

## 🛠️ Tecnologias Utilizadas  
- **Microsoft Azure Vision Studio**  
- **JSON** (para automação e análise de dados)  
- **Git/GitHub** (para versionamento e colaboração)  

## 📷 Exemplo de Imagem  
Abaixo, um exemplo de imagem utilizada no projeto para reconhecimento facial:  


![Imagem Exemplo](![download image azure 1](https://github.com/user-attachments/assets/e59f60dd-c3fc-463c-8179-b33c925398bb)
)  

## 📜 Código JSON Simplificado
Aqui está um exemplo do JSON retornado pelo Azure Vision Studio:
{
  "recognitionModel": "reconhecimento_01",
  "faceRectangle": { "largura": 141, "altura": 201, "esquerda": 470, "topo": 186 },
  "faceLandmarks": {
    "olhoEsquerdo": { "x": 510.5, "y": 256.4 },
    "olhoDireito": { "x": 574.7, "y": 263.7 },
    "nariz": { "x": 538.1, "y": 301.7 },
    "bocaEsquerda": { "x": 502.2, "y": 325 },
    "bocaDireita": { "x": 568.7, "y": 331.8 }
  },
  "atributos": { "mascara": { "tipo": "noMask", "narizEBocaCobertos": false } }
}
📌 Observações
O código JSON acima contém os principais pontos faciais detectados.
Inclui a verificação do uso de máscara facial.


## 📝 Tutorial: Como Reproduzir Este Projeto  

### 1️⃣ Criando um recurso no Azure  
1. Acesse o [Portal do Azure](https://portal.azure.com).  
2. Crie um novo recurso e selecione **"Cognitive Services"**.  
3. Escolha a região e o plano de preço adequado.  
4. Após a criação, anote a **chave de API** e o **endpoint**.  

### 2️⃣ Configurando o Azure Vision Studio  
1. Acesse o [Azure Vision Studio](https://www.microsoft.com/en-us/ai/vision-studio).  
2. Faça login com sua conta do Azure.  
3. Insira a **chave da API** e o **endpoint** no painel de configurações.  
4. Faça upload da imagem desejada para análise.  

### 3️⃣ Processando Imagens com Python  
1. Instale as dependências necessárias:  
   ```sh
   pip install requests
2. Envie uma imagem para análise utilizando uma requisição HTTP

##👨‍💻 Desenvolvido por Maria Eduarda Soares Machado


