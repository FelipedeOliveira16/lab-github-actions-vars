 # DESAFIOS ESCOPO
 
  - *Por que a Secret aparece no log como *** e a variável aparece normalmente? **
  
  A Secret aparece como * porque o GitHub aplica um filtro de segurança automático para evitar que dados sensíveis sejam expostos nos logs.

  - *O Job deploy_app consegue ler a variável BUILD_VERSION criada no Job build_app? Por quê?*

 Não, um job não tem acesso direto às variáveis de outro, já que cada um é executado de forma independente em seu próprio ambiente isolado, normalmente em um runner separado.

 

