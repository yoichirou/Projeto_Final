# CESAE Digital — Projeto Final

Website institucional do **CESAE Digital**, desenvolvido como projeto final de formação. O site apresenta o centro de formação, os cursos disponíveis, as entidades parceiras e os contactos, com um formulário para envio de mensagens.

## Páginas

| Página | Ficheiro | Conteúdo |
| --- | --- | --- |
| Homepage | [index.html](index.html) | Secção de destaque, apresentação do CESAE Digital e cursos em destaque |
| Cursos | [pages/cursos.html](pages/cursos.html) | Lista de cursos: AWS re/Start, Software Developer, Marketing Digital, Data Analyst e Network & Cyber Security |
| Parceiros | [pages/parceiros.html](pages/parceiros.html) | Parcerias e certificações (Cisco, AWS Academy, Check Point, Pearson VUE, entre outras) |
| Contactos | [pages/contactos.html](pages/contactos.html) | Moradas, telefones e emails dos polos do Porto, São João da Madeira e Lisboa, e formulário de contacto |
| Sucesso | [pages/utils/success.html](pages/utils/success.html) | Confirmação apresentada após o envio do formulário |

Todas as páginas partilham a mesma barra de navegação e o mesmo rodapé.

## Tecnologias

- HTML5
- CSS3
- [Bootstrap 5.3](https://getbootstrap.com/) (via CDN)
- [Bootstrap Icons 1.13](https://icons.getbootstrap.com/) (via CDN)

## Estrutura

```
projetofinal/
├── index.html          # Homepage
├── css/                # Estilos de cada página
│   ├── index.css
│   ├── cursos.css
│   ├── parceiros.css
│   └── contactos.css
├── images/             # Logótipos, imagens dos cursos e dos parceiros
└── pages/
    ├── cursos.html
    ├── parceiros.html
    ├── contactos.html
    └── utils/
        └── success.html
```

## Como executar

O projeto é estático e não precisa de instalação.

1. Clonar o repositório:
   ```bash
   git clone https://github.com/yoichirou/Projeto_Final.git
   ```
2. Abrir o ficheiro `index.html` no navegador.

Também é possível usar uma extensão como o **Live Server** do VS Code para recarregar a página automaticamente durante o desenvolvimento.

> É necessária ligação à internet para carregar o Bootstrap e os ícones a partir do CDN.

## Formulário de contacto

O formulário da página de Contactos recolhe nome, email, telemóvel e mensagem. Não existe backend: ao submeter, o utilizador é redirecionado para a página de sucesso e os dados não são guardados nem enviados.

## Autores

- Bruna Gama ([@brunajacby](https://github.com/brunajacby))
- Raquel ([@terruta](https://github.com/terruta))
- Diogo ([@yoichirou](https://github.com/yoichirou))
