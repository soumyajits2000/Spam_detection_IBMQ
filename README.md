# Spam_detection_IBMQ
Hey peeps! Welcome. 
You opened this because the word 'Quantum' fascinated you. Right!? You will be getting loads of excitement and confusion now. Be ready.

Ok, about this project, This project was done by me and my friend (roomie at IISER, Berhampur) Shaswata Karmakar as a part of our Summer Internship program of 2020 at IISER Kolkata. We prepared a spam detection algorithm which works perfectly fine even in real world noisy conditions, on a real quantum computer.

Our main objective was to build an E-mail spam filter which can differentiate between spam and non-spam E-mails. It should be able to perform well in noisy conditions. We have built a quantum machine learning algorithm to train our dataset first and then implement that algorithm to another dataset to check whether it can classify between spam and non-spam or not. We will be doing this whole experiment on a simulator first before moving on to a real quantum computer. We will be taking around 30 mails for our reference and train the set for spam and non-spam. Then we will test the algorithm on a different set of mails.

And for your information we first simulated the whole algorithm on ‘qasm simulator’ provided by ‘Aer’ of ‘qiskit’ as it is noise free (not perfectly ideal though). Then we ran the algorithm on 'ibmq_vigo', a 5-qubit quantum computer and took real world noisy readings on it.

The main caveat of the project is that we cannot add on more features to the code i.e. we wanted to add more words, take larger training sets, etc. However, on doing so, we would fall short of enough computational power which is made cloud-available by IBMQ. 

At present this project might be way too advanced to apply to qComps now. But surely it will be in use when we will be using highly secure quantum internet. 

Adios! 
Soumyajit
