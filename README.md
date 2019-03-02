# tess-film-institute
This repository contains data and python (2.7) scripts developed in collaboration with [Tess Thorsen](https://medium.com/@tess_thorsen) and deals with equality in funding from the Danish Film Institute (DFI).

We found the yearly facts and figures reports from DFI to be lacking with respect to gender related statistics, especially related to funding. The purpose of this code is to take the official numbers from DFI and divide them into a binary category male or female. While we recognize gender as a spectrum we employ these categories as a reflection of lacking gender diversity in the movie industry.

Data is scraped from the [official funding numbers](https://www.dfi.dk/branche-og-stoette/stoette/stottetildelinger) and we focus on manuscript writers (_Manueforfatter_) and directors (_Instruktør_). Writers and directors are divided into male or female categories according to the [danish name registry](https://ast.dk/born-familie/hvad-handler-din-klage-om/navne/navnelister/godkendte-fornavne), which lists legals names by gander. Names which were not included in the registry were added manually based on the self-identification of the person. The registry also contains gender neutral names, however, since none of thise were not present of the data a binary approach applies.

Data was collected around Nov 2018.

__Note:__ The main purpose of the scripts is to generate figures to be used in Tess' PhD. As such, the code is not optimized and in certain places very hacky.