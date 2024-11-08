# Spelling-Orthography-Update
This project uses machine learning to update text from an older spelling orthography to a modern spelling orthography. The focus on this project will be on updating the spelling orthography from the 1908 Chamorro Bible. **Project Status: In Progress**

## About this data
This project uses the text from the 1908 Chamorro Bible, which is a partial translation of the King James Bible. This text can be found and downloaded for free at http://chamorrobible.org/. The 1908 Chamorro Bible contains the four gospels, the Acts of the Apostles, and the Boook of Psalms. This translation was written in an older style, Spanish-influenced spelling orthography, which uses different letters than the current modern orthographies (i.e.: it uses the letter "j" for what is now written with the letter "h"). Some modern letters it does not use at all, with the most notable absence being the glota (') which is used in modern orthographies to indicate glottal stops and affixes. It also collapses multiple words into single words, usually attaching pronouns to the beginning or ends of words (i.e.: *jucantaye* in the old orthgraphy is *hu kantåyi* in more modern orthographies).

## About the training data
As of the date of this project, there is no labelled dataset available for training our models. Therefore, I will be manually creating the training data for this project. I will take a sample of the words in the text, map them to their modern orthography equivalents by hand and use this sample to train the models.

## Benefits of this project
The old-style Spanish orthography makes this text difficult for modern Chamorro language learners and speakers to read. Updating this orthography will provide the following benefits:
- Increased accessibility of the text to the Chamorro people, especially language learners
- Opens future opportunities for text analysis and the creation of additional language-instruction materials
- Invites future opportunities for the use of machine learning and other automated methods for updating older texts
- Provides a potentially viable option for other minority language communities to use machine learning in the processing of their text content

## Features
- Scrapes and cleans the text from ChamorroBible.org
- Imports a small set of manually created sample pairs for our training set
- Training, tuning and evaluating different machine-learning models. (Specifics will be added later)
- An updated word list exported as a .CSV file
- An updated text of the 1908 Chamorro Bible into a more modern orthography
