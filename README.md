# Aquário Digital Core

## Missão
Protocolo de Versionamento e Gestão de Ecossistema — desenvolvimento de um módulo
de controle de qualidade da água para um aquário digital, aplicando o fluxo de
desenvolvimento corporativo em três camadas.

## Camadas do Ambiente
- **develop**: ambiente de desenvolvimento ativo, onde novas features são integradas.
- **stage**: ambiente de testes/homologação, onde as mudanças validadas em develop
  são conferidas antes de ir para produção.
- **main**: ambiente de produção, contendo apenas código validado e estável.

## Módulo: Controle de Qualidade da Água
Classe `ControleQualidadeAgua` responsável por monitorar os níveis de pH e
temperatura da água do aquário, emitindo alertas quando os parâmetros saem da
faixa ideal (pH entre 6.8 e 7.6, temperatura entre 22.0°C e 28.0°C).

## Equipe
- Vinícius