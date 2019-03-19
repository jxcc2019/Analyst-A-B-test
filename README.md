# Analyst-A-B-test
The third project in Udacity nanodegree of Data Analyst

—————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————
03/18/19 update suggestion from Udacity mentors.
using loops to simulate 10000 can take a considerable amount of time vs using numpy 

new_converted_simulation = np.random.binomial(n_new, p_new,  10000)/n_new
old_converted_simulation = np.random.binomial(n_old, p_old,  10000)/n_old
p_diffs = new_converted_simulation - old_converted_simulation
