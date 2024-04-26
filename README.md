Script para processamento Digital de Imagens LandSat 5 e 9 e Sentinel 2 em ambiente Colab

Problema: o analista gasta muito tempo procurando uma imagem viável (sem nuvens) para a area do shapefile e, ainda precisa baixar as bandas corretas e fazer a compposição das bandas (merge).

Descrição: O script está configurado para salvar todos os arquivos do processamento no seu Google Drive, dentro do caminho indicado. Também está configurado para buscar as imagens a partir de um determinado intervalo temporal. É necessário tambem colocar qual fuso UTM está o shapefile para criação do arquivo de altimetria min e max da propriedade.
A primeira coisa que vai acontecer é dar permissão de acesso ao drive e fazer o envio do arquivo shapefile. o script vai fazer a busca pelas imagens landsat 5 e lista-las da mais recente para mais antiga com a porcentagem de nuvens. Depois insira o numero da imagem que voce deseja, pré-visualize a imagem se estiver conforme, escreva "Sim"
O mesmo processo ocorrerá na Landsat 9 e no sentinel 2, repita o processo de escolha, visualização e confirma.
A composição de bandas será feita e salva no Drive.
e será excluido o arquivo de limite matricula e propriedade (shapefile) da pasta do Drive.
