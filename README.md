# Volcánicas Scraper & Vision 

This repository contains scripts to support **Volcánicas**, a Latin American feminist journalism project, by automating content extraction from key sources and exploring AI-assisted video transcription.

## Overview

- Scrapes articles from Volcanicas links to extract structured information: title, URL, and detailed content.
- Designed to enhance research and editorial workflows with feminist tech principles: autonomy, transparency, and ethical storytelling.

 
## **Goal:** 

Create a clean and consistent schema (`title`, `url`, `content`) to prepare data for **embedding generation and use in a RAG (Retrieval-Augmented Generation) system**.

## Result
```json
{
  "title": "Summary of Volcánicas - Nosotras Page",
  "url": "https://volcanicas.com/nosotras/#volcanicas",
  "content": "Volcánicas is a feminist Latin American investigative journalism project dedicated to rigorous, feminist, and audacious reporting that advances women's and LGBTI rights across Latin America and the Caribbean. The team comprises 100% feminists and operates under Fundación Hoja Blanca-ONG, a nonprofit organization reinvesting all resources into the project with transparent annual financial reports. Founded by Catalina Ruiz-Navarro and Matilde de los Milagros Londoño Jaramillo, Volcánicas emerged as an independent platform following critical investigative work on harassment allegations in the media industry.\n\nTheir editorial policy emphasizes dignity, protection, and agency for sources, especially women, trans, and non-binary persons, employing feminist, decolonial, and anti-racist approaches. They cover critical thematic areas including sexual harassment and abuse using a rigorous verification method, sexual and reproductive rights, LGBTIQ+ issues, anti-racism, and political and social protest among others.\n\nThe organization is composed of a diverse team of feminist journalists, editors, and content creators from Latin America, supported by an advisory board of experienced advocates and professionals in gender equality and social justice.\n\nVolcánicas strives to create a safe space for feminist voices and stories, ensuring rigorous, ethical journalism that challenges patriarchal norms and supports marginalized communities through investigative storytelling."
}

