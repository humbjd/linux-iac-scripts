

---

# Projeto de Automação de Controle de Acesso - `iacl.sh`

Este projeto, denominado `linux-iac-scripts`, contém um script de shell (`iacl.sh`) desenvolvido para automatizar a criação de diretórios, grupos de usuários, usuários e a configuração de permissões nesses diretórios. O objetivo é facilitar a administração e o controle de acesso em sistemas baseados em Unix.

## Índice

- [Descrição](#descrição)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Descrição

O script `iacl.sh` automatiza as seguintes tarefas:

1. Criação de diretórios.
2. Criação de grupos de usuários.
3. Criação de usuários e adição aos grupos.
4. Configuração de permissões específicas para os diretórios.

Este script é útil para administradores de sistemas que precisam gerenciar acessos de usuários e permissões de forma eficiente.

## Pré-requisitos

Antes de usar o `iacl.sh`, verifique se o seu sistema atende aos seguintes requisitos:

- Sistema operacional baseado em Unix (Linux, macOS, etc.)
- Acesso root ou privilégios de sudo
- Shell Bash

## Instalação

1. Clone este repositório para o seu ambiente local:

    ```bash
    git clone https://github.com/humbjd/linux-iac-scripts.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd linux-iac-scripts
    ```

3. Conceda permissão de execução ao script:

    ```bash
    chmod +x iacl.sh
    ```

## Uso

Para executar o script, use o seguinte comando:

```bash
sudo ./iacl.sh
```

O script solicitará as informações necessárias, como nomes de diretórios, grupos e usuários, e configurará tudo conforme as especificações.

### Exemplos de Uso

1. **Criação de Diretórios:**

    O script perguntará o nome dos diretórios a serem criados.

2. **Criação de Grupos:**

    O script solicitará o nome dos grupos de usuários a serem criados.

3. **Criação de Usuários:**

    O script solicitará o nome dos usuários e a quais grupos eles devem ser adicionados.

4. **Configuração de Permissões:**

    O script aplicará permissões específicas aos diretórios criados.

## Estrutura do Projeto

```
linux-iac-scripts/
│
├── iacl.sh
├── README.md
└── LICENSE
```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorar este projeto.

1. Faça um fork do projeto
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça um push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

