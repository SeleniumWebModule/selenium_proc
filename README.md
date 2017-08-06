# selenium_proc
Gerenciamento dos componentes para a execução dos testes funcionais

Esse projeto irá controlar todos os componentes necessários para a execução dos testes funcionais. 

Alguns exemplos: 

  - Consumir o serviço que disponibilizará os testes que deverão ser executados
  - Acionar os módulos necessários para os testes (banco, mantis, reportes)
  - Consumir o serviço para reportar as etapas que estão sendo executadas, por exemplo:
      - banco sendo provisionado
      - teste em execução (tela, componente ...)
  - Consumir o serviço de retorno com o status final do teste
