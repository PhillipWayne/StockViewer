node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		bat 'nuget restore ChampionCharts.sln'
		bat "\"${tool 'MSBuild'}\" ChampionCharts.sln /p:Configuration=Release /p:Platform=\"Any CPU\" /p:ProductVersion=1.0.0.${env.BUILD_NUMBER}"

	stage 'Archive'
		archive 'StockViewer/bin/Release/**'

}
