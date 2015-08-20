Quick Start

Command to run: 

python bootstrap_3P_9_7.py config.txt

but well, it won't succeed until you set up correct paths or filenames in the configuration file "config.txt".

Explanations

please open the file config.txt first, here you'll see a list of parameter lines, each line separated by a tab key.

Let's look at them one by one.

raw_file_list points to a file that contains a list of paths to real data files.

agent_seed_file points to the seed file of actors.

purpose_effect_seed_file points to the seed file of purpose phrases.

output_file_path points to a directory path where the learned event dictionaries and other intermediate files will be saved.

dependency_parsing_script_file points to the stanford dependency parser's script file, this will be needed to parse those candidate event sentences.
