repo
===============

Quick and dirty maven repository for snapshot and release artifacts 

Add the following repositories to your settings.xml:

            <repositories>
                <repository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>repo</id>
					<url>http://adamcin.net/repo/releases/</url>
                </repository>
                <repository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
                    <id>repo</id>
					<url>http://adamcin.net/repo/snapshots/</url>
                </repository>
            </repositories>
            <pluginRepositories>
                <pluginRepository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>repo</id>
					<url>http://adamcin.net/repo/releases/</url>
                </pluginRepository>
                <pluginRepository>
                    <snapshots>
                        <enabled>true</enabled>
                    </snapshots>
                    <id>repo</id>
					<url>http://adamcin.net/repo/snapshots/</url>
                </pluginRepository>
            </pluginRepositories>
