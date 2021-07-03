# Resume-Classification-keyword-spotter-using-flashtext
Used libraries
Pdfminer for reading pdfs
flash text for key word spotting

Input - foldres with pdf resumes
Process
  Reading all the resumes in the folder and convertiong them as data frame
  Cleaning resume data by removing newline char.
  Creating seperate dict with list of keywords for each category
  passing the dict into flashtext as keyword
  passing the resume doc to flashtext to get keuwords
  
  
