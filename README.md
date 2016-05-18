# Maven Archetype
Passos para a geração de seu archetype personalizado <br>
1 - Clone este projeto <br>
2 - Navegue até a pasta do projeto <br>
3 - Execute o codigo <strong><em>mvn archetype:create-from-project</em></strong> <br>
4 - Recorte a pasta <strong><em>../target/../archetype</em></strong> pra um local de sua preferencia  <br>
5 - Vá até a pasta recorta, e execute o comando <strong><em>mvn clean install</em></strong> <br>
6 - Caso deseje alterar as configurações de seu archetype, navegue
Pronto, seu archetype já está definido, pra gerar um novo projeto , execute <br><strong><em>mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeGroupId=io.github.jass2125 -DarchetypeArtifactId=default-project</strong></em>
