# explorando-recursos-azure

1. Entradas no GitHub Copilot (Sugestão de Código Automática)
O GitHub Copilotfunciona

✅ Exemplo 1: Autocompletar Código com Comentário
🔹 Input (Comentário escrito no editor)

# Criar uma função que verifica se um número é primo
🔹 Output (Código gerado automaticamente pelo Copilot)

def eh_primo(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
✅ Exemplo 2: Criar uma API Simples com FastAPI
🔹 Input (Comentário para Copiloto gerar código)

# Criar uma API usando FastAPI para retornar "Olá, mundo!"
🔹 Saída (Código sugerido pelo Copiloto)

from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"message": "Olá, mundo!"}

2. Entradas para Geração de Texto com OpenAI (GPT-4)
O GPT-4 d

✅ Exemplo 1: Crie um E-mail Profissional
Entrada (Prompt enviado para a API do OpenAI)

Plaintex

Escreva um e-mail profissional solicitando orçamento para consultoria em segurança cibernética.
🔹 Saída (Resposta do GPT-4)

Assunto: Solicitação de Orçamento para Consultoria em Segurança Cibernética  

Prezado(a) [Nome],  

Gostaria de solicitar um orçamento para consultoria em segurança cibernética. Poderia fornecer detalhes sobre os serviços oferecidos, custos e disponibilidade?  

Aguardo seu retorno.  

Atenciosamente,  
[Seu Nome]  
🔹 Dica:Seja **claroclaro e objetivonenhum pedido para

✅ Exemplo 2: Gerar código com GPT-4 via API
🔹 Input (Código em Python para chamar a API da OpenAI)

import openai

openai.api_key = "SUA_CHAVE_API"

resposta = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[{"role": "user", "content": "Crie um script Python que lê um arquivo CSV e calcula a média de uma coluna."}]
)

print(resposta["choices"][0]["message"]["content"])
🔹 Saída: G

3. Inputs para Geração de Imagens com DALL·E
✅ Exemplo 1: Criar uma Arte de Paisagem
🔹Input (Prompt para geração de imagem)

texto simples

Uma floresta encantada com árvores brilhantes e um rio de néon fluindo sob um céu estrelado.
🔹 Saída: DALL·E cria

🔹 Dica: Incluicores, iluminação e estilopor favor

🎙 4. Entradas para Transcrição de Áudio com Whisper

✅ Exemplo 1: Transcrever um arquivo de áudio
Entrada (código em Python para transcrição)

import whisper

model = whisper.load_model("base")
result = model.transcribe("audio.mp3")
print(result["text"])
Saída: Texto transcrito

🔹 Dica: Useáudio limpo e sem ruídospor favor

🎯 Conclusão
Entradas do sistema operacionalsãbons resultados com GitHub Copilot e OpenAI .

✔ Sem copiloto, use **comentárioscomentários claros pa
✔Não GPT-4 , escreva **promprompts detalhadospar
✔ **Não DALL·E, descreva imagensmáxima riqueza de detalhes .
✔Sem Sussurro,áudio de boa qualidadepara transcr
