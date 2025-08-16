# 📖 Bíblia Online

Este projeto reúne diferentes traduções da **Bíblia em Português Brasileiro** em formato **JSON**, oferecendo uma interface web simples, responsiva e elegante (com **Bootstrap 4**) para leitura e navegação por **testamentos, livros, capítulos e versículos**.

## 🚀 Funcionalidades

- Seleção de versão da Bíblia
- Filtro de livros e busca global por palavras
- Navegação entre capítulos anterior/próximo
- Cópia rápida de versículos
- Interface responsiva (desktop, notebook, tablet e celular)
- Layout acessível e leve

## 📂 Estrutura do Projeto

```sh
/
├── avemaria/
│   └── bibliaAveMaria.json
│   └── index.html
├── almeidacorrigidafiel/
│   └── acf.json
│   └── index.html
├── almeidarevisadaimprensabiblica/
│   └── aa.json
│   └── index.html
├── novaversaointernacional/
│   └── nvi.json
│   └── index.html
└── index.html  ← página inicial com seleção das versões
```

Cada pasta contém os arquivos JSON correspondentes e a interface de leitura (HTML/JS).

## 📚 Versões disponíveis

- **Nova Versão Internacional (NVI)**
- **Almeida Corrigida e Fiel (ACF)**
- **Almeida Revisada Imprensa Bíblica (AA - Imprensa Bíblica)**
- **Ave Maria (católica)**

## 🙌 Créditos & Referências

Um agradecimento especial aos criadores e mantenedores dos repositórios que disponibilizaram as versões em JSON:

- [thiagobodruk/biblia](https://github.com/thiagobodruk/biblia)  
  Contém as versões: **NVI**, **ACF** e **AA (Imprensa Bíblica)** em português do Brasil.  

- [fidalgobr/bibliaAveMariaJSON](https://github.com/fidalgobr/bibliaAveMariaJSON)  
  Contém a versão **Ave Maria** em JSON, contribuindo com a tradição católica.  

## 🛠️ Tecnologias usadas

- **HTML5 / CSS3**
- **Bootstrap 4**
- **JavaScript (ES6+)**
- **JSON** (estrutura dos textos bíblicos)

## 💡 Como usar

1. Faça o clone do repositório:
```sh
   git clone https://github.com/AlanMartines/bibliasemfronteiras.git
````

2. Abra o arquivo `index.html` diretamente no navegador **ou** sirva o projeto em um servidor local (por exemplo: `Live Server` no VSCode).

3. Escolha a versão desejada da Bíblia e navegue pelos livros, capítulos e versículos.

## 📜 Licença

Os textos bíblicos em JSON pertencem aos respectivos autores dos repositórios citados em **Créditos & Referências**.
O código da interface está sob a licença **MIT**, livre para uso e modificação.
