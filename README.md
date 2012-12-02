repo
===============

Quick and dirty maven repository for snapshot and release artifacts 

Add the following repositories to your settings.xml:

            <repositories>
                <repository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
					<url>http://adamcin.net/repo/releases/</url>
                    <id>adamcin-m2-repo</id>
                </repository>
                <repository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
					<url>http://adamcin.net/repo/snapshots/</url>
                    <id>adamcin-m2-repo</id>
                </repository>
            </repositories>
            <pluginRepositories>
                <pluginRepository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
					<url>http://adamcin.net/repo/releases/</url>
                    <id>adamcin-m2-repo</id>
                </pluginRepository>
                <pluginRepository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
					<url>http://adamcin.net/repo/snapshots/</url>
                    <id>adamcin-m2-repo</id>
                </pluginRepository>
            </pluginRepositories>
