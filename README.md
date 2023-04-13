# Q-AProject
This project takes a set of articles (some business related ones are provided) and uses a cross encoder to output a a ranking of the articles probability to answer a given question. It gives the user 3 articles which can be used however they are needed
................................................There are multiple different resources provided, including: a set of text files from articles found on yahoo finance. These articles are finance based and all pertain to electric vehicle stocks and comapnies. These do not have do be used with this code, but they are there for convenience. 
.................................................There is also a chatGPT prompt provided. One thing I wanted to do was integrate the chatGPT API into this project so that it can return paraphrased versions of the text, elaborate on stuff or give a direct answer based on the best ranked text and the question asked, but because chatGPT API is payed if I want to do that I just use the online website. If you want to try using chatGPT to help with this I provided a prompt that has worked well. It is not perfect but it provides good answers and prevents chatGPT from making up things that are not in the text.
................................................ In the main code there are 11 spaces for importing files. If you want to import fewer files delete some of the rows, if you want to import more files copy one section of the code starting from the "with open" until the.append(textX). Make sure to name the new file a new number and append the correct one. No other parts of the code need to be changed. 
