# League Insights Analyzer
Welcome to the League Insights Analyzer! This tool allows you to analyze player statistics for the popular online multiplayer game, League of Legends. Gain insights into your performance or that of other players by leveraging the wealth of data provided by Riot Games' API. This project is developed for the CS210 Introduction to Data Science course.

## Overview

This project focuses on the analysis of League of Legends data to derive insights into gaming performance and predict match outcomes. The analysis incorporates various gaming metrics, including kills, deaths, assists, gold earned, and total damage dealt to champions. Additionally, qualitative information such as the champion name is considered to capture the unique attributes associated with each champion.

## What is League of Legends?
League of Legends (LoL) is a highly popular multiplayer online battle arena (MOBA) game developed and published by Riot Games. In this fast-paced and strategic game, players assume the roles of unique champions with distinct abilities and battle it out in teams to achieve victory.

## How to Use the Tool
Prerequisites
- **Riot API Key**: Obtain your Riot API key from the Riot Developer Portal.
- **Python**: Ensure you have Python installed on your system.

## Features

- **Data**: Easily obtain your League of Legends match data by changing the "api_key" varible to your API code.
- **Performance Metrics**: View detailed performance metrics, including KDA, CS per minute, and more.
- **Visualizations**: Explore interactive visualizations to gain insights into your gameplay trends.

## Note

- Feel free to replace the default **PUUID** with your own unique puuid id and adjust the **region** variable to match the region you are playing in. This allows you to customize the analysis and observe results specific to your gaming data. This tool relies on the Riot Games API to fetch player statistics. Ensure that you have a valid Riot API key and follow Riot's terms of service.
- You can retrieve your **PUUID** by accessing the following link: https://**region**.api.riotgames.com/lol/summoner/v4/summoners/by-name/**name**?api_key=**key**, where you should replace **region** with your region code, **name** with your summoner name, and **key** with your Riot API key.

