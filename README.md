# Relatório: Automação do Terraform com GitHub Actions

## Introdução

Este tutorial detalha como usar o GitHub Actions para automatizar o workflow do Terraform, focando na utilização com o Terraform Cloud. As GitHub Actions facilitam a integração contínua, permitindo automação completa desde a construção até a implantação de software.

## Tecnologia e Conceitos Aprendidos

- **Terraform**: Uma ferramenta de infraestrutura como código (IaC) que permite definir e provisionar a infraestrutura de TI usando uma linguagem de configuração declarativa.
- **GitHub Actions**: Serviço de CI/CD integrado ao GitHub para automatizar workflows.
- **Terraform Cloud**: Plataforma da HashiCorp que oferece um ambiente colaborativo e gerenciado para o Terraform, facilitando a escalabilidade e a gestão de infraestrutura.

## Workflow de Automação

1. **Configuração Inicial**: Criação de um workspace no Terraform Cloud e configuração de um repositório GitHub usando um template específico.
2. **Workflows de GitHub Actions**:
   - **Plano**: Geração e revisão de um plano de implantação para cada commit em uma branch de pull request.
   - **Aplicação**: Aplicação da configuração quando atualizada a branch `main`.
3. **Testes e Merges**: Criação e merge de um pull request para testar o workflow configurado.

## Conclusão

O uso combinado de Terraform Cloud e GitHub Actions para automatizar a implantação de servidores web acessíveis publicamente demonstra uma poderosa capacidade de integração e automação para gestão de infraestrutura como código.



