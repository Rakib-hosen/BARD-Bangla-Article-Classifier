# BARD Bangla Article Classifier
Video Demo: <a href="https://bit.ly/BARD_VIDEO_DEMO"> bit.ly/BARD_VIDEO_DEMO </a> <br/>
Dataset Link: <a href="https://bit.ly/BARD_DATASET"> bit.ly/BARD_DATASET </a> <br/>

<h2>Dataset Details</h2>
<table>
<tr>
<td align="center">Category  </td><td align="center">  No. of Documents  </td><td align="center">  No. of Words  </td><td align="center">  Average Sentences per Document  </td><td align="center">  Average words per Sentence</td>
</tr><tr>
<td align="center">State </td><td align="center">  242860  </td><td align="center">  57019465  </td><td align="center">  18.50  </td><td align="center">  13.356</td>
</tr>
</table>



CategoryNo.  ofDocumentsNo.  ofWordsAverageSentencesperDocumentAveragewordsperSentenceState2428605701946518.5013.356Economy18982491514120.1813.378International32203709611118.4712.493Entertainment31293670656321.7010.236Sports508881239741522.8011.069




In the literature article classification is well studied, where several supervised leaning models have been proposed by utilizing large textual data corpus. Despite several comprehensive textual dataset available for different language, only a few small datasets available for Bangla articles. As a result, a couple works address the Bangla document classification and could not able to learn sophisticated supervised learning model. In this work, we curated a large dataset of Bangla article which help us to train several supervised learning model using some sophisticate features, such as word2vec. As word2vec preserves semantic features, it shows superior performance in text classification. Moreover, Neural Network with word2vec features shows promising performance compared to other state-of-the-art-work in the text classification. 
    \par Furthermore, we deployed our proposed Bangla content classifier as a web application, which is accessible at \url{www.bard2018.pythonanywhere.com}  and the video demo of this application is available here: \url{bit.ly/BARD_VIDEO_DEMO}. Additionally, we open-sourced the BARD dataset(\url{bit.ly/BARD_DATASET}) and source code of this work().
