## Exercise 1

For each of these questions, provide the commands you used:

1. Create a project directory called Exercise. Which commands did you use?
`mkdir Exercise`
2. In the directory, create all the sub-directories you would need for a Bioinformatics Project
`mkdir -p data/raw results scripts
3. Download [this fasta](https://raw.githubusercontent.com/kipkurui/IntroductoryLinux/master/Data/nrf1_seq.fa) file to the appropriate directory in your project
`wget https://raw.githubusercontent.com/kipkurui/IntroductoryLinux/master/Data/nrf1_seq.fa` 
4. Extract the sequence headers and save into a file `sequence_names.txt` in the appropriate directory
`grep '>' nrf1_seq.fa > sequence_names.txt`
5. Save the commands you used in question 4 in a script file `extract_seq.sh`
