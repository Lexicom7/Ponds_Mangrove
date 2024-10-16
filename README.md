# **Analysis of the influence of aquaculture pond construction on mangrove forests in Asian countries.**

## Introduction
Almost one third of the world's mangrove forests have been lost due to deforestation in the last 50 years (Alongi, 2002; Barbier, 2014). Along with coastal development, another major cause of global mangrove deforestation is the development of shrimp farms to support a booming export fishing industry (Barbier and Cox, 2004; Hamilton, 2020; Richards and Friess, 2016), with global demand for shrimp continuing to rise (Anderson et al., 2019). A study by Hamilton (2013) found that 51.9% of the original mangrove areas have been deforested between the 1970s and after 2004, with commercial aquaculture accounting for 28% of the total mangrove loss in eight countries: Indonesia, Brazil, Bangladesh, India, Thailand, Vietnam, Ecuador and China.

This notebook series studies the influence of aquaculture pond construction on mangrove forests through spatial analysis of two datasets: Aquaculture dynamics (Ottinger et al., 2021) and the Global Mangrove Watch version 3 (Bunting et al., 2018; Bunting, Rosenqvist, Hilarides, Lucas, & Thomas, 2022; Bunting, Rosenqvist, Hilarides, Lucas, Thomas, et al., 2022).

The general objective is to look for a relationship between the activation or construction of aquaculture ponds and the loss of mangrove forest extent. For this purpose, several notebooks were made for the different steps in the analysis process:


1. DataPreparation: The datasets are divided by countries in Asia and the layers are organised in separate folders.
2.   DataAnalysis: We proceed to analyse the relationship between both datasets using geoprocessing tools and working with dataframes.
MangroveChangeAnalysis: Only the Global Mangrove Watch dataset is analysed and an analysis of the dynamics within Asia is made.
4. GraphicOutput: The results of the analysis are visualised for interpretation and understanding.
5.   HexagonMangrove: Mapping the cumulative mangrove forest loss from 1996 to 2020 in the ten countries with the highest mangrove loss in Asia.
6.   HexagonPonds: Mapping cumulative mangrove loss due to pond construction from 1996 to 2019.
