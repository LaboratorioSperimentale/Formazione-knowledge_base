# Digital Text Annotation and Analysis with Catma 7

## Index
- Introduction: What is Catma?
- 1. Registration and Log-In
- 2. Project Module
- 3. Tags Module
- 4. Annotate Module
- 5. Analyze Module

## Introduction: What is Catma?
**Catma** (Computer Assisted Text Markup Analysis) is a free **open source annotation tool**, particularly useful for manual text annotation. Unlike other tools, Catma supports collaborative work as well. Texts and annotations can be analyzed using different criteria and queries, such as word frequency, annotation category or proximity between words.

The program can be divided into **4 modules**, each one corresponding to a specific function:
- Project module:
- Tags module
- Annotate module
- Analyze module (which includes visualization and semi-automatic annotation).

## 1. Registration and Log-In
First of all, you have to create your Catma account: you can either use a Google account or a private mail. After signing up you will receive a verification e-mail to the address you used during your registration. Once your e-mail address has been verified, you can complete your profile by choosing a username and a password.

## 2. Project Module
As soon as you log in, you can either choose *"New Project"* or *"Join a Project"* (in the latter case, the owner of the project has to add you through your username or via real-time invitation).
Once you enter the project module, you will be able to see and manage the components of your project (documents, tag sets, members etc.). In this section you can upload texts from your local computer or add a URL (by clicking on the button "+"),  as well as export collections or documents. 
In a group work you can create your own annotation collection. Nevertheless, the actions you are allowed to do depend on your role in the project: each role corresponds to [specific permissions](https://catma.de/documentation/roles-and-permissions/). For example:
- **Owner**: The owner has every possible right  on the group, such as creating/deleting documents, tagsets, annotation collections or adding/removing members from the project.
- **Partner**: A partner almost has the same rights as the owner, except for a few aspects: they cannot remove or add a member, nor can they delete the project.
- **Observer**: An observer can only view documents, tagsets or annotation collections, but they cannot add or edit them in any way.

The **sync button** allows each member to synchronize their project progress in order to share their uploaded documents, annotations or new tags.
In collaborative projects, the **switch view button** allows to switch between two view modes,which are “*synchronize*” (which shows the current state of all work that has been integrated + anything that u have done in top of that, as an individual) and “*latest contribution*” (the project enters a read-only state that allows you to see what the other members have been up to).

## 3. Tags Module
Once you have uploaded your resources, presumably you also want to create a **tagset** (the tags you are going to work with on your project). After creating a tag, you can also specify its properties in order to further qualify it.
Catma also offers you the possibility to create **sub-tags** (i.e. a tag which is subordinated to another tag in order to qualify it better).

## 4. Annotate Module
In this module, after selecting the annotation collection and the tag set you want to work with, you can start **annotating a document**. While working in this section you will have the text on the left side of your screen and the tagset you have chosen on the right side.  
If you want to  add a tag you just need to select the text passage and press the right button of your mouse: in this way, the tagset you have chosen will appear, so that you can choose the tag you want. 
Let's see some important funtions of this module:
- *Discontinuous passages*: by clicking on the book icon on the lower left corner you can add one single annotation to discontinuous passages in the document. 
- *Overlapping tags*: You can also apply different tags to the same text passage. 
- *Comments*: Another important function is the possibility of leaving comments on the document: if you don't feel sure about which tag best suits a text passage, you can add a comment on the text, so that your teammates can help you (to do so you just have to select the text èassage and a comment icon will appear).

## 5. Analyze Module
In this section you can explore texts and annotations with **queries** and **visualization options**.
Queries allow you to analyze, explore and evaluate text or annotation data. To [execute a query](https://catma.de/how-to/query-language/) on documents or annotation collections you have three options:
- You can either select a **predefined query**; 
- You can use the **query builder** on the left side of the screen to create your own query. This option is particularly useful when you want to analyze some particularly detailed data about your text (e.g. the words that appear more than 20 times in your document, how many times a specific word appears, how many time a tag appears etc.). You can build a query based on 5 criteria: by word or phrase pattern, by grade of similarity, by tag, by collocation or by frequency. With this function, Cadma offers you the possibility of creating very complex queries too (for example, how many times a specific word appears next to another word).
- You can **type a query** directly, if you're familiar with the Catma query language.

After choosing a query or creating your own one, the results appear in a box beneath the query fields and headline with the query itself, a timestamp and the total number of results. You can also change the grouping of the results (for example by tag).

Another option to explore your query results is the visualization. Cadma offers four different ways to visualize your query results (which appear on the right part of your screen in this module):
- **Key words in context visualization**: This option shows your results in their textual context (both left context and right context) in the form of a table. You can also use the KWIC visualization to create annotations semi-automatically.
- **Distribution visualization**: It shows the distribution of query results across the text. For example, you can create your own query (a specific word or a tag) and see how many times these entities appear in the text with a graph. Catma also allows you to save the graph as SVG or PNG.
- **Wordcloud visualization**: The higher the frequency of the word in your document, the larger it appears in the word cloud. Just like the previous point, you can save the image as SVG or as PNG.
- **Doubletree visualization**: It displays the keyword and context results as a browsable tree showing both the preceding and following context of one particular word.