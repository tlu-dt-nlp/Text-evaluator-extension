# Chrome extension of the ELLE Writing Evaluator (Tekstihindaja)
To use the web application in the Chrome browser, download the repository, type `chrome://extensions` to the address bar, enable the developer mode and choose `Load unpacked`. Select the `Text-evaluator-extension-main` folder. Then activate the extension, choose `Details` and pin it to the toolbar. To analyze a text on a website or your own writing (e.g., an email), select the text with your cursor and click on the extension icon 'T'.

The development is described in the following thesis:
> Rosenfeld, V. (2023). [_Teksti automaathindaja brauserilaiendi arendus_](https://www.etera.ee/s/l5BHZzo0ST) [Thesis, Tallinn University Haapsalu College]. E-research library ETERA.

The extension is based on the [Writing Evaluator](https://elle.tlu.ee/corrector) tool of the ELLE language learning and analysis environment (ELLE repository can be found [here](https://github.com/centre-for-educational-technology/evkk)). Spelling correction uses the Jamspell algorithm. Proficiency evaluation (A2-C1) relies on morphological, lexical and surface (word and sentence length based) features. Various scores of complexity (LIX, SMOG, Flesch-Kincaid grade level) and lexical diversity (RTTR, CTTR, MTLD and HDD) are calculated. Text complexity is estimated on a three-level scale: 'Easy' - 'Medium' - 'Difficult' ('Kerge' - 'Keskmine' - 'Raske' in Estonian).

An example of using the correction view of the extension (Rosenfeld, 2023):
![Screenshot of the Writing Evaluator Chrome extension.](http://www.tlu.ee/~kais/ELLE_materjalid/rosenfeld2023_diplomitoo_naide.png)
