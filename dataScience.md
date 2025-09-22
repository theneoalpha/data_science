Data Science 







Data Science is the process of collecting, cleaning, analyzing, and interpreting data to make informed decisions.



Data Science Life Cycle   	Data science is mix of Hacking skills(specific  tool decide karna ), Maths and statstics knowledge(statistics and probability knowledge), and substantive expertise(domain specific logo se baat karna - like for medical data science doctor se baat karna)




	Data science life cycle - process used to extrat insights from data

steps : 
 	
	Step 1 : Problem defination (apni problem ko sahi se samjhna)

	Step 2 : Data collection (uss problem ke according relevant kya data collect karni hai)

	Step 3 : Data cleaning / data pre-processing (80% time yahi consume hota hai data scientist ka)  	Step 4 : Data exploration

	Step 5 : Model building (agar simple python function se kaam ho jaye to huge model nahi banate , simple function se work kar lenge)

	Step 6 : Model Evolution ( bane hue model ko aur optimise karna)


	Step 7 : Deployment (dashboard ya ui bana ke dena taaki end user easy way me samjh paye)

	Step 8 : Communication and reporting

	Step 9 : Maintenance




Anaconda , Langauage , Mini conda, Google Colab & Jupyter Notebook   	Python : Mainly hum python language use karte hai kyoki iski kaafi libraries mil jati hai AI Ml related and also 

	Anaconda : Ye compelete bunddle hai , jiske andar 
				- Python
				- Multiple data science libraries
				- Ye isolated environment Conda(manage software version ) bhi provide karta hai harr project ke liye

	Juypter Notebook : Most of the ML developers use jupyter notebook kyoki isme hum code ke sath comment(markdown) bhi de sakte hai ,
				- cell by cell execution
				

	Mini-conda - Lighter version of Anaconda 
	Google Colab : Advance version of Juypter notebook , isme hame GPU bhi mil jata hai and ye apna GPU use karta hai , hamara hardware use nahi hota


	


Anaconda Navigator , Anaconda Prompt and Conda


	Ananconda navigator - GUI to manage all libraries and all 
	Anaconda Prompt - (only in case of windows laptop): command prompt jaha se hum cammand ke thorugh action perform kar sake,
						,mac me automatic hota hai terminal se

	Conda - command line utility , Ye package manager hai jo saara envireonment (just like docker ) and package manage karta hai   				conda list                               				( just like git command )
	
				conda env list							 (it gives the overall available environment list)
		
				conda create -n myenv					(naya env banana)
	 			conda activate myenv						( activate karna env ko)
				conda create -n myenv python=3.11 			( particular env me specific python use karna )


Juypter Notebook and Juypter lab

	Why juypter Notebook ?  why not normal vs code? 		- hum data science me code ko chunks(shells) me run karna chahte hai , like run 4th line first then run 2nd line

	
			How/Step to Install jupyter and   jupyter  lab 				- Juypter Notebook 						conda install jupyter  						jupyter notebook


							- Mainly isme shells ka concept hota hai , number assign hota hai shells incremented order wrt edit then run hota hai usi 									sequence me

				- Juypter Lab : JupyterLab is the next-generation interface for Jupyter, offering a more advanced and flexible workspace.
						conda install  jupyter  lab 	

HOW TO WORK WITH JUPYTER LAB  	What is the difference between Control+Enter and  Shift+Enter

	Control + Enter = run the code but focus remain is in same chunk(block)
	Shift + Enter = run the code and also increment the focus to new chunk(block)



	GENERALLY WE USE JUPYTER LAB AS USER FRIENDLY AND EASY
 

