# Spelling-Orthography-Update
This project uses machine learning to update text from an older spelling orthography to a modern spelling orthography. The focus on this project will be on updating the spelling orthography from the 1908 Chamorro Bible. **Project Status: In Progress**

## About this data
This project uses the text from the 1908 Chamorro Bible, which is a partial translation of the King James Bible. This text can be found and downloaded for free at http://chamorrobible.org/. The 1908 Chamorro Bible contains the four gospels, the Acts of the Apostles, and the Boook of Psalms. This translation was written in an older style, Spanish-influenced spelling orthography, which uses different letters than the current modern orthographies (i.e.: it uses the letter "j" for what is now written with the letter "h"). Some modern letters it does not use at all, with the most notable absence being the glota (') which is used in modern orthographies to indicate glottal stops and affixes. It also collapses multiple words into single words, usually attaching pronouns to the beginning or ends of words (i.e.: *jucantaye* in the old orthgraphy is *hu kantåyi* in more modern orthographies).

## About the training data
As of the date of this project, there is no labelled dataset available for training our models. Therefore, I will be manually creating the training data for this project. I will take a sample of the words in the text and map them to their modern orthography equivalents by hand.

## Benefits of this project
The old-style Spanish orthography makes this text difficult for modern Chamorro language learners and speakers to read. Updating this orthography will provide the Chamorro people with a valuable, free resource in the Chamorro language, which can be used to support their language learning efforts. It may also support future researchers in the study of the Chamorro language, particularly in assessing how the language hase changed in the over 100 years since the 1908 Chamorro Bible's initial publication. Finally, exploring machine learning methods for updating the orthography may open new possibilities for taking other, older texts and automating the process of updating their orthographies to make them more widely accessible for modern audiences. This also invites the possibility of machine learning, natural language processing, and other automated methods to be a viable and accessible option for minority communities and languages such as Chamorro, where resources to undertake such work manually may be extremely limited or unavailable.

## Features
- Scrapes the text directly from ChamorroBible.org and cleans it
- Importing a small set of manually created sample pairs for our training set
- Training, tuning and evaluating different machine-learning models. (Specifics will be added later)
- An updated word list, and the results exported as a .CSV file
- An updated text of the 1908 Chamorro Bible
