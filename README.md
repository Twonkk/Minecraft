# Minecraft



compiled spigot/craftbucket from BuildTools.jar.. Should you want to do so your self, you can just follow the bellow steps

1) mkdir "some magical name" <-- rename to whatever you want without ""

2) cd "some magical name"

3) wget -0 https://hub.spigotmc.org/jenkins/job/BuildTools/lastSuccessfulBuild/artifact/target/BuildTools.jar

4) chmod +x BuildTools.jar

5) git config --global --unset core.autocrlf

6) run java -jar BuildTools.jar



thats pretty much it... if you want a certain version of spigot for say MC 1.8 then you would need to add "--rev 1.8" to step 6. (minus "")

java -jar BuildTools.jar --rev 1.8 or java -jar BuildTools.jar --rev 1.10.2 for MC 1.10.2

Enjoy

