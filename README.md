# Introduction au framework NHibernate pour la plateforme .NET

[Introduction au framework NHibernate pour la plateforme .NET (2011)](https://stahe.github.io/nhibernate-dotnet-dec-2011/)

Ce dépôt accompagne un cours d'introduction à **NHibernate**, présenté comme l'équivalent .NET du framework Java **Hibernate**. Le document propose une vue d'ensemble concise de l'utilisation d'un **ORM** (*Object Relational Mapper*) dans l'écosystème .NET.

## Présentation

Un ORM est un ensemble de bibliothèques permettant à une application exploitant une base de données de manipuler celle-ci **sans écrire explicitement de requêtes SQL** et **sans dépendre des particularités du SGBD utilisé**.

Ce support constitue une **introduction succincte** à NHibernate. Pour une étude plus approfondie, le document recommande l'ouvrage suivant :

- **NHibernate in Action**
- **Auteur** : Pierre-Henri Kuaté
- **Éditeur** : Manning
- **ISBN-13** : 978-1932394924

## Niveau et prérequis

Dans une échelle **débutant / intermédiaire / avancé**, ce document se situe au niveau **intermédiaire**.

Sa compréhension suppose plusieurs prérequis, notamment :

1. **C# 2008**  
   *Apprentissage du langage C# Version 3.0 avec le Framework .NET 3.5*

2. **Spring IoC pour .NET**  
   Présentation des bases de l'**Inversion of Control (IoC)** et de l'**injection de dépendances (Dependency Injection)** avec **Spring.NET**

Le document indique également, au début de certains paragraphes, des conseils de lecture renvoyant vers ces supports préalables.

## Outils utilisés

L'étude de cas s'appuie sur des outils librement disponibles sur le web, dans leurs versions mentionnées en **décembre 2011** :

- **NHibernate 3.2**
- **Spring.NET 1.3.2**  
  Utilisé ici pour les bibliothèques facilitant l'exploitation de NHibernate
- **log4net 1.2.10**  
  Framework de journalisation utilisé par NHibernate
- **NUnit 2.5**  
  Framework de tests unitaires, équivalent .NET de JUnit
- **Pilote ADO.NET 6.4.4 pour MySQL 5**

## Objectif du support

Ce cours vise à introduire les bases de **NHibernate** dans un contexte .NET, en montrant comment simplifier l'accès aux données grâce à une approche orientée objets, tout en s'appuyant sur des outils complémentaires de configuration, de journalisation et de tests.

