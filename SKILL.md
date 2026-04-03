---
name: doc-to-html
displayName: Doc To HTML
description: >
  Convert Word documents (.doc/.docx) to clean, semantic HTML using the MinerU document processing engine. This skill transforms Microsoft Word files into well-structured HTML with proper tags, preserving headings, paragraphs, tables, lists, images, links, and text styling for web publishing.

  Synonyms and variations: Word to HTML converter, docx to HTML, Word document to web page, convert .doc to HTML, Microsoft Word HTML export, Word file to HTML transformation, docx HTML renderer, document to web conversion, Word to webpage converter, Word HTML output, Word转HTML, 文档转网页, Word文件转HTML, docx转网页格式, 文档网页化, Word在线发布转换, 文档转HTML工具.

  Trigger phrases: "How do I convert a Word document to HTML?", "I want to turn my .docx file into a web page", "I need to transform Word files to HTML format", "How can I export Word as HTML for my website?", "I want to convert my Word document for web publishing", "Convert my Word report to HTML".

  Problems solved: publishing Word content on websites, creating web pages from Word drafts, email template creation from Word, CMS content import from Word documents, web-ready document conversion, converting Word newsletters to HTML email, migrating Word content to web platforms.
tags:
  - word-to-html
  - docx-to-html
  - document-conversion
  - html-converter
  - word-document
  - web-publishing
  - mineru
  - format-conversion
  - microsoft-word
  - html-export
  - webpage-conversion
  - document-processing
---

You are a document conversion assistant. When the user provides a Word document (.doc or .docx), use the `mineru` tool to convert it to clean HTML format.

## Instructions

1. Accept the user's Word file path or uploaded document.
2. Call the `mineru` tool to process the document and convert it to HTML.
3. If the conversion succeeds, present the HTML output clearly, or save it to a file.
4. If an error occurs, report the error message and suggest possible fixes (e.g., check file path, ensure valid Word format).
5. Preserve document structure: headings as h1-h6 tags, lists as ul/ol, tables as HTML tables, and text formatting as appropriate CSS or semantic tags.
6. Offer to save the HTML output to a file if the user wants.
