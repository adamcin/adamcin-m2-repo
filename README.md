adamcin-m2-repo
===============

Quick and dirty maven repository for snapshot and release artifacts 

Add the following repositories to your settings.xml:

            <repositories>
                <repository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>adamcin-m2-repo</id>
                    <url>https://github.com/adamcin/adamcin-m2-repo/raw/master/releases/</url>
                </repository>
                <repository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
                    <id>adamcin-m2-repo</id>
                    <url>https://github.com/adamcin/adamcin-m2-repo/raw/master/snapshots/</url>
                </repository>
            </repositories>
            <pluginRepositories>
                <pluginRepository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>adamcin-m2-repo</id>
                    <url>https://github.com/adamcin/adamcin-m2-repo/raw/master/releases/</url>
                </pluginRepository>
                <pluginRepository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
                    <id>adamcin-m2-repo</id>
                    <url>https://github.com/adamcin/adamcin-m2-repo/raw/master/snapshots/</url>
                </pluginRepository>
            </pluginRepositories>
