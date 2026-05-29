## Fork by Zain ul Abdeen (S5309493)
### Changes Made:
- Fixed Windows/Cygwin path conversion bug in isabelle_api.py
- Fixed session_id extraction in cli.py  
- Fixed finished_ok result verification in isabelle_api.py
- Added Groq API support in planner/skeleton.py
- Added ML Reranker training data

- ---------------------------------------------------------------------------------

The following are simple suits for testing functionalities only:

- logic.txt
- sets.txt
- nat.txt
- lists.txt

The following are easy (even the hol_main_hard one is easy, it's just slightly harder than the other ones) synthetic datasets that only require HOL built-in libraries to prove. These are used to generate synthetic logs/data for training.

- hol_main_easy_goals.txt
- hol_main_mid_goals.txt
- hol_main_hard_goals.txt

The following are testing datasets that are not used in training or tuning parameters.

- hol_main_easy_goals_test.txt
- hol_main_mid_goals_test.txt
- hol_main_hard_goals_test.txt

The mini_f2f folder contains the extracted Isabelle/HOL goals from the Mini-F2F dataset. There are 244 goals in the validation set and 244 goals in the test set.

The putnambench folder contains the extracted Isabelle/HOL goals from the PutnameBench dataset.

Users can verify the extracted datasets using instructions in the README.md in the root directory.

The python files are self-explanatory helpers.
