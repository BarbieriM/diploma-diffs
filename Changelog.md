# Changelog

## Versão 1.03

- Permitido caractere "-" na definição de ato normativo
- Permitido multiplas assinaturas na Tag DocumentacaoAcademicaRegistro
- Permitido modalidade "Semi Presencial" para fora do sistema federal (NSF)
- Permitida a situação "Trancado" em TConceito
- Permitida a situação "EstudoAproveitado" em TConceito
- Criação de um campo de texto livre para anotaçoes no registro chamado InformacoesAdicionais
- Flexibilizado o numero de habilitações em NomeHabilitacao
- Flexibilizado da existência de habilitações em NomeHabilitacao
- Criação do título de Psicólogo
- Criação do título de Tecnologo
- Permitido S/N em TNumeroAto
- Criação da Tag Enfase para Curso
- Flexibilização da presença de ENADE em históricos de segundas vias
- Criação da Escala de Conceitos RM
- Criação do Campo OutraPortaria para Faculdades com Prerrogativa de Registro
- Flexibilização da Representação de Carga horária em Horas-aula e horas-relogio (Decimal)
- Ajustar Anexo da IN para refletir código de validação em caso de número de registro unico

## Versão 1.04

- Ao informar a tramitação do MEC no caso de Recredenciamentos da emissora está exigindo os dados da portaria que ainda não existem.
- Quantidades de Dígitos no RG
- Ser mais claro em relação a Certificado PJ vs Certificado e-CNPJ e A1 vs A3
- Padronização de termos Documentação Academica e Registro Academico na IN
- Dentro de <DiplomasFiscalizados> encapsular cada diploma em um <DiplomaFiscalizado>
- Dentro de <DiplomasAnulados> encapsular cada diploma em um <DiplomaAnulado>
- Gerar arquivos de Exemplo faltantes
- Tornar obrigatória a especificação do emec das IES Registradoras e Emissoras
- Adicionar o tipo de ato: "Deliberação" na lista de valores TTipoAto
- Refatorar TTitulo - Sai Psicologo e altera Técnico para Tecnólogo
- Explicar melhor o fluxo de geração dos XMLs na IN
- Permtir a emissão de arquivos XML de testes/homologação sem validade legal
- Mover DataColacaoGrau e DataExpedicaoDiploma para XML do Documentacao Academica
- Histórico em XML destacado do XML de Registro Acadêmico
- Arquivo XML de fiscalização pelo MEC
- Repensar o processo de anulação de diplomas
- DocumentacaoComprobatoria com espaço
- Flexibilização de sexo e nomeSocial de Genitor
- Exemplo de diploma digital esta coassinatura no adra
- Permitir associar uma data as habiltiações
- Criar script para geração de release
- Criar a estrutura do versão 1.04 de graduação
- Nomenclaturas - ENADE
- Retirar maxOccurs="1" em TTermoResponsabilidade
- Atividades complementares no histórico
- Script para autogerar changelogs
- Descrever composição do código localização no anexo III para cursos sem e-MEC
- Trazer para o XML a identificação dos cargos dos assinantes
