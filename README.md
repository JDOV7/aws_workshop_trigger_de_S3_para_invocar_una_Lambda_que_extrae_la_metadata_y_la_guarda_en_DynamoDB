# AWS Workshop: Trigger de S3 para invocar una Lambda que extrae la metadata y la guarda en DynamoDB


## Tabla de Contenidos

1. [🚀 Informacion General](#-informacion-general)
2. [💻 Tecnologias](#-tecnologias)
3. [📚 Recursos](#-recursos)
4. [✒️ Autores](#%EF%B8%8F-autores)

## 🚀 Informacion General

---

<p align="justify">
Para este ejercicio vamos a crear un pequeño proceso que cuando se suba un objeto a S3 y se cumplan las siguientes condiciones:
</p>


- El objeto se suba a una carpeta en especifico
- El objeto es de una extensión en especifico


<p align="justify">

Se invocara un trigger que ejecutara una función Lambda que va a extraer los metadatos del objeto y se guardara dicha metadata como un nuevo ítem en una tabla creada en DynamoDB, además usando CloudWatch se imprimirá dicha metadata también
</p>



## 💻 Tecnologias

---

<div align="center">

<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/AWS_LAMBDA-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" alt="AWS Lambda" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/AWS S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white" alt="AWS S3" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/DynamoDB-FF9900?style=for-the-badge&logo=amazondynamodb&logoColor=white" alt="AWS DynamoDB" />&nbsp;&nbsp;
<img src="https://img.shields.io/badge/AWS CloudWatch-FF9900?style=for-the-badge&logo=amazoncloudwatch&logoColor=white" alt="AWS CloudWatch" />&nbsp;&nbsp;

</div>

## 📚 Recursos

---
- [Notion Pasos](https://hazel-orange-2f0.notion.site/Tutorial-Uso-de-un-trigger-de-S3-para-invocar-una-Lambda-que-extrae-la-metadata-y-la-guarda-en-Dyna-7305fc9d64584822a5bc9837030263f6?pvs=4)


## ✒️ Autores

---

* **Ochoa Virgen Jesus Daniel** - *Desarrollador* - [JDOV7](https://github.com/JDOV7)