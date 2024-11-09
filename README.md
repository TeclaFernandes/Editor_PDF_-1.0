# PDF Editor

Este projeto é um Editor de PDF simples desenvolvido em Python utilizando as bibliotecas `customtkinter`, `PyPDF2`, `PIL` e outras para manipulação de arquivos PDF. Ele permite que o usuário realize diversas operações em arquivos PDF, como dividir, mesclar e rotacionar páginas, tudo por meio de uma interface gráfica.

## Funcionalidades

O editor de PDF oferece as seguintes funcionalidades:

### 1. **Dividir PDF**
   - Permite ao usuário dividir um arquivo PDF em partes específicas, selecionando o intervalo de páginas a ser extraído.
   
### 2. **Mesclar PDFs**
   - Permite ao usuário mesclar vários arquivos PDF em um único documento.
   
### 3. **Rotacionar PDF**
   - Permite ao usuário rotacionar um arquivo PDF em graus de 90°, 180° ou 270°.
   
### 4. **Interface Gráfica**
   - A interface gráfica é construída usando o `customtkinter`, com botões e entradas para selecionar arquivos, diretórios e opções de configuração.

### 5. **Gerenciamento de Arquivos**
   - O usuário pode selecionar locais de armazenamento para salvar os PDFs divididos ou mesclados.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para o desenvolvimento.
- **customtkinter**: Biblioteca utilizada para criar a interface gráfica do usuário.
- **PyPDF2**: Biblioteca para manipulação de arquivos PDF (divisão, mesclagem e rotação de páginas).
- **Pillow (PIL)**: Biblioteca para manipulação de imagens, utilizada na interface gráfica.
- **Tkinter**: Biblioteca padrão de Python para construção de interfaces gráficas.

## Instalação

Para rodar este projeto, você precisará das seguintes bibliotecas:

```bash
pip install customtkinter PyPDF2 Pillow
```

## Como Usar

**1. Iniciar o Aplicativo:** Execute o script Python.

**2. Menu:** O menu principal oferece opções para:
- Dividir PDF
- Mesclar PDF
- Girar PDF
- Sobre (informações do desenvolvedor)

**3. Operações:**

- **Dividir PDF:** Escolha o arquivo PDF, defina o intervalo de páginas e selecione o local para salvar o arquivo dividido.
- **Mesclar PDFs:** Selecione vários arquivos PDF e escolha o local para salvar o arquivo mesclado.
- **Girar PDF:** Selecione o arquivo PDF e o grau de rotação (90°, 180° ou 270°) e escolha o local para salvar o arquivo rotacionado.

**4. Interface:** Após selecionar a operação desejada, a interface apresentará campos de entrada para os parâmetros necessários e botões de ação.

## Exemplo de Uso

**1. Dividir PDF:**

- Selecione um arquivo PDF.
- Defina as páginas de início e fim.
- Escolha um diretório para salvar o PDF dividido.

**2. Mesclar PDF:**

- Selecione múltiplos arquivos PDF.
- Escolha um diretório para salvar o PDF mesclado.
- Rotacionar PDF:

**3. Selecione um arquivo PDF.**

- Escolha o grau de rotação (90°, 180° ou 270°).
- Escolha um diretório para salvar o PDF rotacionado.

## Contribuições

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. Fork este repositório.
2. Crie uma nova branch para suas alterações (git checkout -b minha-nova-branch).
3. Faça as alterações e commit (git commit -am 'Adicionar nova funcionalidade').
4. Envie para o repositório remoto (git push origin minha-nova-branch).
5. Crie uma Pull Request.

## Licença

Este projeto é licenciado sob a licença MIT - consulte o arquivo LICENSE para mais informações.

## Contato

Se você tiver alguma dúvida ou sugestão, fique à vontade para abrir uma issue ou enviar um e-mail para [teclafernandes70@gmail.com](teclafernandes70@gmail.com).

```bash
Esse `README.md` cobre a descrição do projeto, tecnologias usadas, como instalar e usar o programa, e ainda fornece detalhes sobre como colaborar no projeto. Certifique-se de ajustar os detalhes de contato e qualquer outra informação específica do seu projeto.
```