# SimPy
2021-06-03

```shell
/home/cwm/git/git.c-w-m/sim_dev/.tox/sim_dev39/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 9:46 AM ...
simpy37 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/simpy37
simpy37 installdeps: pytest, pytest-benchmark, jupyterlab, ipykernel, pandas
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
simpy37 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
simpy37 installed: anyio==3.1.0,argon2-cffi==20.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==3.3.0,certifi==2021.5.30,cffi==1.14.5,chardet==4.0.0,decorator==5.0.9,defusedxml==0.7.1,entrypoints==0.3,idna==2.10,importlib-metadata==4.5.0,iniconfig==1.1.1,ipykernel==5.5.5,ipython==7.24.1,ipython-genutils==0.2.0,jedi==0.18.0,Jinja2==3.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-server==1.8.0,jupyterlab==3.0.16,jupyterlab-pygments==0.1.2,jupyterlab-server==2.6.0,MarkupSafe==2.0.1,matplotlib-inline==0.1.2,mistune==0.8.4,nbclassic==0.3.1,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.0,numpy==1.20.3,packaging==20.9,pandas==1.2.4,pandocfilters==1.4.3,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,pluggy==0.13.1,prometheus-client==0.11.0,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,py-cpuinfo==8.0.0,pycparser==2.20,Pygments==2.9.0,pyparsing==2.4.7,pyrsistent==0.17.3,pytest==6.2.4,pytest-benchmark==3.4.1,python-dateutil==2.8.1,pytz==2021.1,pyzmq==22.1.0,requests==2.25.1,Send2Trash==1.5.0,-e git+https://github.com/c-w-m/simpy.git@e71134d1a22721973a46eece7edee99a96429065#egg=simpy&subdirectory=../../../src/simpy,six==1.16.0,sniffio==1.2.0,terminado==0.10.0,testpath==0.5.0,toml==0.10.2,tornado==6.1,traitlets==5.0.5,typing-extensions==3.10.0.0,urllib3==1.26.5,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.1.0,zipp==3.4.1
simpy37 run-test-pre: PYTHONHASHSEED='734426919'
simpy37 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/simpy37/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 10001 -- --doctest-glob= tests
Launching pytest with arguments --doctest-glob= tests --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 149 items / 10 deselected / 139 selected

tests/test_condition.py::test_operator_and PASSED                        [  0%]
tests/test_condition.py::test_operator_and_blocked PASSED                [  1%]
tests/test_condition.py::test_operator_or PASSED                         [  2%]
tests/test_condition.py::test_operator_nested_and 
tests/test_condition.py::test_operator_nested_or 
tests/test_condition.py::test_nested_cond_with_error 
tests/test_condition.py::test_cond_with_error 
tests/test_condition.py::test_cond_with_nested_error 
tests/test_condition.py::test_cond_with_uncaught_error PASSED            [  6%]
tests/test_condition.py::test_iand_with_and_cond 
tests/test_condition.py::test_iand_with_or_cond PASSED                   [  7%]
tests/test_condition.py::test_ior_with_or_cond PASSED                    [  8%]
tests/test_condition.py::test_ior_with_and_cond PASSED                   [  9%]
tests/test_condition.py::test_immutable_results PASSED                   [ 10%]
tests/test_condition.py::test_shared_and_condition 
tests/test_condition.py::test_shared_or_condition 
tests/test_condition.py::test_condition_value 
tests/test_condition.py::test_result_order 
tests/test_condition.py::test_nested_result_order 
tests/test_condition.py::test_all_of_empty_list PASSED                   [ 14%]
tests/test_condition.py::test_any_of_empty_list 
tests/test_environment.py::test_event_queue_empty PASSED                 [ 15%]
tests/test_environment.py::test_run_negative_until PASSED                [ 16%]
tests/test_environment.py::test_run_resume PASSED                        [ 17%]
tests/test_environment.py::test_run_until_value 
tests/test_environment.py::test_run_with_processed_event 
tests/test_environment.py::test_run_with_untriggered_event 
tests/test_event.py::test_succeed 
tests/test_event.py::test_fail PASSED                                    [ 20%]
tests/test_event.py::test_names 
tests/test_event.py::test_value PASSED                                   [ 22%]
tests/test_event.py::test_unavailable_value PASSED                       [ 23%]
tests/test_event.py::test_triggered PASSED                               [ 23%]
tests/test_event.py::test_callback_modification PASSED                   [ 24%]
tests/test_event.py::test_condition_callback_removal 
tests/test_event.py::test_condition_nested_callback_removal 
tests/test_exceptions.py::test_error_forwarding 
tests/test_exceptions.py::test_no_parent_process 
tests/test_exceptions.py::test_crashing_child_traceback PASSED           [ 28%]
tests/test_exceptions.py::test_exception_chaining 
tests/test_exceptions.py::test_invalid_event PASSED                      [ 29%]
tests/test_exceptions.py::test_exception_handling PASSED                 [ 30%]
tests/test_exceptions.py::test_callback_exception_handling PASSED        [ 30%]
tests/test_exceptions.py::test_process_exception_handling 
tests/test_exceptions.py::test_process_exception_chaining 
tests/test_exceptions.py::test_sys_excepthook 
tests/test_interrupts.py::test_interruption 
tests/test_interrupts.py::test_concurrent_interrupts 
tests/test_interrupts.py::test_concurrent_interrupts_and_events PASSED   [ 35%]
tests/test_interrupts.py::test_init_interrupt 
tests/test_interrupts.py::test_interrupt_terminated_process PASSED       [ 36%]
tests/test_interrupts.py::test_multiple_interrupts PASSED                [ 37%]
tests/test_interrupts.py::test_interrupt_self 
tests/test_interrupts.py::test_immediate_interrupt 
tests/test_interrupts.py::test_interrupt_event 
tests/test_interrupts.py::test_concurrent_behaviour 
tests/test_process.py::test_start_non_process 
tests/test_process.py::test_get_state 
tests/test_process.py::test_target PASSED                                [ 42%]
tests/test_process.py::test_wait_for_proc 
tests/test_process.py::test_return_value PASSED                          [ 43%]
tests/test_process.py::test_child_exception 
tests/test_process.py::test_interrupted_join 
tests/test_process.py::test_interrupted_join_and_rejoin 
tests/test_process.py::test_error_and_interrupted_join 
tests/test_resources.py::test_resource 
tests/test_resources.py::test_resource_capacity 
tests/test_resources.py::test_resource_context_manager 
tests/test_resources.py::test_resource_slots PASSED                      [ 49%]
tests/test_resources.py::test_resource_continue_after_interrupt 
tests/test_resources.py::test_resource_release_after_interrupt 
tests/test_resources.py::test_resource_immediate_requests 
tests/test_resources.py::test_resource_cm_exception 
tests/test_resources.py::test_resource_with_condition 
tests/test_resources.py::test_resource_with_priority_queue 
tests/test_resources.py::test_sorted_queue_maxlen 
tests/test_resources.py::test_get_users 
tests/test_resources.py::test_preemptive_resource 
tests/test_resources.py::test_preemptive_resource_timeout_0 
tests/test_resources.py::test_mixed_preemption PASSED                    [ 57%]
tests/test_resources.py::test_nested_preemption 
tests/test_resources.py::test_container 
tests/test_resources.py::test_container_get_queued 
tests/test_resources.py::test_initial_container_capacity 
tests/test_resources.py::test_container_get_put_bounds 
tests/test_resources.py::test_container_init_capacity[None-args0] 
tests/test_resources.py::test_container_init_capacity[None-args1] 
tests/test_resources.py::test_container_init_capacity[None-args2] 
tests/test_resources.py::test_container_init_capacity[ValueError-args3] 
tests/test_resources.py::test_container_init_capacity[ValueError-args4] PASSED [ 64%]
tests/test_resources.py::test_container_init_capacity[ValueError-args5] 
tests/test_resources.py::test_container_init_capacity[ValueError-args6] PASSED [ 66%]
tests/test_resources.py::test_store PASSED                               [ 66%]
tests/test_resources.py::test_initial_store_capacity[Store] PASSED       [ 67%]
tests/test_resources.py::test_initial_store_capacity[FilterStore] 
tests/test_resources.py::test_store_capacity 
tests/test_resources.py::test_store_cancel 
tests/test_resources.py::test_priority_store_item_priority 
tests/test_resources.py::test_priority_store_stable_order 
tests/test_resources.py::test_filter_store PASSED                        [ 71%]
tests/test_resources.py::test_filter_store_get_after_mismatch 
tests/test_resources.py::test_filter_calls_best_case PASSED              [ 73%]
tests/test_resources.py::test_filter_calls_worst_case PASSED             [ 74%]
tests/test_resources.py::test_immediate_put_request PASSED               [ 74%]
tests/test_resources.py::test_immediate_get_request PASSED               [ 75%]
tests/test_rt.py::test_rt[0.1] 
tests/test_rt.py::test_rt[0.05] 
tests/test_rt.py::test_rt[0.15] 
tests/test_rt.py::test_rt_multiple_call PASSED                           [ 78%]
tests/test_rt.py::test_rt_slow_sim_default_behavior 
tests/test_rt.py::test_rt_slow_sim_no_error PASSED                       [ 79%]
tests/test_rt.py::test_rt_illegal_until PASSED                           [ 80%]
tests/test_rt.py::test_rt_sync PASSED                                    [ 81%]
tests/test_rt.py::test_run_with_untriggered_event PASSED                 [ 82%]
tests/test_timeout.py::test_discrete_time_steps 
tests/test_timeout.py::test_negative_timeout 
tests/test_timeout.py::test_timeout_value 
tests/test_timeout.py::test_shared_timeout 
tests/test_timeout.py::test_triggered_timeout PASSED                     [ 85%]
tests/test_util.py::test_start_delayed PASSED                            [ 86%]
tests/test_util.py::test_start_delayed_error PASSED                      [ 87%]
tests/test_util.py::test_subscribe PASSED                                [ 87%]
tests/test_util.py::test_subscribe_terminated_proc PASSED                [ 88%]
tests/test_util.py::test_subscribe_with_join 
tests/test_util.py::test_subscribe_at_timeout 
tests/test_util.py::test_subscribe_at_timeout_with_value 
tests/test_util.py::test_all_of 
tests/test_util.py::test_all_of_generator 
tests/test_util.py::test_wait_for_all_with_errors PASSED                 [ 92%]
tests/test_util.py::test_all_of_chaining 
tests/test_util.py::test_all_of_chaining_intermediate_results PASSED     [ 94%]
tests/test_util.py::test_all_of_with_triggered_events PASSED             [ 94%]
tests/test_util.py::test_any_of PASSED                                   [ 95%]
tests/test_util.py::test_any_of_with_errors PASSED                       [ 96%]
tests/test_util.py::test_any_of_chaining 
tests/test_util.py::test_any_of_with_triggered_events 
tests/test_util.py::test_empty_any_of 
tests/test_util.py::test_empty_all_of 
tests/test_util.py::test_all_of_expansion 

====================== 139 passed, 10 deselected in 2.41s ======================

PASSED                 [  2%]PASSED                  [  3%]PASSED              [  4%]PASSED                     [  5%]PASSED              [  5%]PASSED                  [  7%]PASSED                [ 10%]PASSED                 [ 11%]PASSED                     [ 12%]PASSED                        [ 12%]PASSED                 [ 13%]PASSED                   [ 15%]PASSED                   [ 17%]PASSED          [ 18%]PASSED        [ 19%]PASSED                                 [ 20%]PASSED                                   [ 21%]PASSED              [ 25%]PASSED       [ 25%]PASSED                   [ 26%]PASSED                  [ 27%]PASSED                 [ 28%]PASSED         [ 31%]PASSED         [ 32%]PASSED                     [ 33%]PASSED                       [ 33%]PASSED              [ 34%]PASSED                     [ 35%]PASSED                     [ 38%]PASSED                [ 38%]PASSED                    [ 39%]PASSED               [ 40%]PASSED                     [ 41%]PASSED                             [ 41%]PASSED                         [ 43%]PASSED                       [ 44%]PASSED                      [ 45%]PASSED           [ 46%]PASSED            [ 46%]PASSED                            [ 47%]PASSED                   [ 48%]PASSED            [ 48%]PASSED   [ 50%]PASSED    [ 51%]PASSED         [ 51%]PASSED               [ 52%]PASSED             [ 53%]PASSED        [ 53%]PASSED                 [ 54%]PASSED                           [ 55%]PASSED                 [ 56%]PASSED       [ 56%]PASSED                   [ 58%]PASSED                           [ 58%]PASSED                [ 59%]PASSED          [ 60%]PASSED            [ 61%]PASSED [ 61%]PASSED [ 62%]PASSED [ 63%]PASSED [ 64%]PASSED [ 65%]PASSED [ 68%]PASSED                      [ 69%]PASSED                        [ 69%]PASSED        [ 70%]PASSED         [ 71%]PASSED     [ 72%]PASSED                                    [ 76%]PASSED                                   [ 76%]PASSED                                   [ 77%]PASSED               [ 79%]PASSED                   [ 82%]PASSED                      [ 83%]PASSED                         [ 84%]PASSED                        [ 84%]simpy39 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/simpy39
simpy39 installdeps: pytest, pytest-benchmark, jupyterlab, ipykernel, pandas
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
simpy39 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
simpy39 installed: anyio==3.1.0,argon2-cffi==20.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==3.3.0,certifi==2021.5.30,cffi==1.14.5,chardet==4.0.0,decorator==5.0.9,defusedxml==0.7.1,entrypoints==0.3,idna==2.10,iniconfig==1.1.1,ipykernel==5.5.5,ipython==7.24.1,ipython-genutils==0.2.0,jedi==0.18.0,Jinja2==3.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-server==1.8.0,jupyterlab==3.0.16,jupyterlab-pygments==0.1.2,jupyterlab-server==2.6.0,MarkupSafe==2.0.1,matplotlib-inline==0.1.2,mistune==0.8.4,nbclassic==0.3.1,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.0,numpy==1.20.3,packaging==20.9,pandas==1.2.4,pandocfilters==1.4.3,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,pluggy==0.13.1,prometheus-client==0.11.0,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,py-cpuinfo==8.0.0,pycparser==2.20,Pygments==2.9.0,pyparsing==2.4.7,pyrsistent==0.17.3,pytest==6.2.4,pytest-benchmark==3.4.1,python-dateutil==2.8.1,pytz==2021.1,pyzmq==22.1.0,requests==2.25.1,Send2Trash==1.5.0,-e git+https://github.com/c-w-m/simpy.git@e71134d1a22721973a46eece7edee99a96429065#egg=simpy&subdirectory=../../../src/simpy,six==1.16.0,sniffio==1.2.0,terminado==0.10.0,testpath==0.5.0,toml==0.10.2,tornado==6.1,traitlets==5.0.5,urllib3==1.26.5,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.1.0
PASSED                      [ 89%]PASSED                     [ 89%]PASSED          [ 90%]PASSED                                   [ 91%]PASSED                         [ 92%]PASSED                          [ 93%]PASSED                          [ 97%]PASSED             [ 97%]PASSED                             [ 98%]PASSED                             [ 99%]PASSED                         [100%]simpy39 run-test-pre: PYTHONHASHSEED='734426919'
simpy39 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/simpy39/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 20001 -- --doctest-glob= tests
Launching pytest with arguments --doctest-glob= tests --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 149 items / 10 deselected / 139 selected

tests/test_condition.py::test_operator_and 
tests/test_condition.py::test_operator_and_blocked 
tests/test_condition.py::test_operator_or PASSED                         [  2%]
tests/test_condition.py::test_operator_nested_and PASSED                 [  2%]
tests/test_condition.py::test_operator_nested_or PASSED                  [  3%]
tests/test_condition.py::test_nested_cond_with_error PASSED              [  4%]
tests/test_condition.py::test_cond_with_error PASSED                     [  5%]
tests/test_condition.py::test_cond_with_nested_error PASSED              [  5%]
tests/test_condition.py::test_cond_with_uncaught_error PASSED            [  6%]
tests/test_condition.py::test_iand_with_and_cond 
tests/test_condition.py::test_iand_with_or_cond 
tests/test_condition.py::test_ior_with_or_cond 
tests/test_condition.py::test_ior_with_and_cond 
tests/test_condition.py::test_immutable_results PASSED                   [ 10%]
tests/test_condition.py::test_shared_and_condition PASSED                [ 10%]
tests/test_condition.py::test_shared_or_condition PASSED                 [ 11%]
tests/test_condition.py::test_condition_value PASSED                     [ 12%]
tests/test_condition.py::test_result_order PASSED                        [ 12%]
tests/test_condition.py::test_nested_result_order PASSED                 [ 13%]
tests/test_condition.py::test_all_of_empty_list PASSED                   [ 14%]
tests/test_condition.py::test_any_of_empty_list 
tests/test_environment.py::test_event_queue_empty 
tests/test_environment.py::test_run_negative_until 
tests/test_environment.py::test_run_resume PASSED                        [ 17%]
tests/test_environment.py::test_run_until_value PASSED                   [ 17%]
tests/test_environment.py::test_run_with_processed_event PASSED          [ 18%]
tests/test_environment.py::test_run_with_untriggered_event PASSED        [ 19%]
tests/test_event.py::test_succeed PASSED                                 [ 20%]
tests/test_event.py::test_fail PASSED                                    [ 20%]
tests/test_event.py::test_names 
tests/test_event.py::test_value 
tests/test_event.py::test_unavailable_value 
tests/test_event.py::test_triggered 
tests/test_event.py::test_callback_modification PASSED                   [ 24%]
tests/test_event.py::test_condition_callback_removal PASSED              [ 25%]
tests/test_event.py::test_condition_nested_callback_removal PASSED       [ 25%]
tests/test_exceptions.py::test_error_forwarding PASSED                   [ 26%]
tests/test_exceptions.py::test_no_parent_process PASSED                  [ 27%]
tests/test_exceptions.py::test_crashing_child_traceback PASSED           [ 28%]
tests/test_exceptions.py::test_exception_chaining 
tests/test_exceptions.py::test_invalid_event 
tests/test_exceptions.py::test_exception_handling 
tests/test_exceptions.py::test_callback_exception_handling 
tests/test_exceptions.py::test_process_exception_handling PASSED         [ 31%]
tests/test_exceptions.py::test_process_exception_chaining PASSED         [ 32%]
tests/test_exceptions.py::test_sys_excepthook PASSED                     [ 33%]
tests/test_interrupts.py::test_interruption PASSED                       [ 33%]
tests/test_interrupts.py::test_concurrent_interrupts PASSED              [ 34%]
tests/test_interrupts.py::test_concurrent_interrupts_and_events PASSED   [ 35%]
tests/test_interrupts.py::test_init_interrupt 
tests/test_interrupts.py::test_interrupt_terminated_process 
tests/test_interrupts.py::test_multiple_interrupts 
tests/test_interrupts.py::test_interrupt_self PASSED                     [ 38%]
tests/test_interrupts.py::test_immediate_interrupt PASSED                [ 38%]
tests/test_interrupts.py::test_interrupt_event PASSED                    [ 39%]
tests/test_interrupts.py::test_concurrent_behaviour PASSED               [ 40%]
tests/test_process.py::test_start_non_process PASSED                     [ 41%]
tests/test_process.py::test_get_state PASSED                             [ 41%]
tests/test_process.py::test_target PASSED                                [ 42%]
tests/test_process.py::test_wait_for_proc 
tests/test_process.py::test_return_value 
tests/test_process.py::test_child_exception PASSED                       [ 44%]
tests/test_process.py::test_interrupted_join PASSED                      [ 45%]
tests/test_process.py::test_interrupted_join_and_rejoin PASSED           [ 46%]
tests/test_process.py::test_error_and_interrupted_join PASSED            [ 46%]
tests/test_resources.py::test_resource PASSED                            [ 47%]
tests/test_resources.py::test_resource_capacity PASSED                   [ 48%]
tests/test_resources.py::test_resource_context_manager PASSED            [ 48%]
tests/test_resources.py::test_resource_slots PASSED                      [ 49%]
tests/test_resources.py::test_resource_continue_after_interrupt 
tests/test_resources.py::test_resource_release_after_interrupt PASSED    [ 51%]
tests/test_resources.py::test_resource_immediate_requests PASSED         [ 51%]
tests/test_resources.py::test_resource_cm_exception PASSED               [ 52%]
tests/test_resources.py::test_resource_with_condition PASSED             [ 53%]
tests/test_resources.py::test_resource_with_priority_queue PASSED        [ 53%]
tests/test_resources.py::test_sorted_queue_maxlen PASSED                 [ 54%]
tests/test_resources.py::test_get_users PASSED                           [ 55%]
tests/test_resources.py::test_preemptive_resource PASSED                 [ 56%]
tests/test_resources.py::test_preemptive_resource_timeout_0 PASSED       [ 56%]
tests/test_resources.py::test_mixed_preemption PASSED                    [ 57%]
tests/test_resources.py::test_nested_preemption PASSED                   [ 58%]
tests/test_resources.py::test_container PASSED                           [ 58%]
tests/test_resources.py::test_container_get_queued PASSED                [ 59%]
tests/test_resources.py::test_initial_container_capacity PASSED          [ 60%]
tests/test_resources.py::test_container_get_put_bounds PASSED            [ 61%]
tests/test_resources.py::test_container_init_capacity[None-args0] PASSED [ 61%]
tests/test_resources.py::test_container_init_capacity[None-args1] PASSED [ 62%]
tests/test_resources.py::test_container_init_capacity[None-args2] PASSED [ 63%]
tests/test_resources.py::test_container_init_capacity[ValueError-args3] PASSED [ 64%]
tests/test_resources.py::test_container_init_capacity[ValueError-args4] PASSED [ 64%]
tests/test_resources.py::test_container_init_capacity[ValueError-args5] 
tests/test_resources.py::test_container_init_capacity[ValueError-args6] 
tests/test_resources.py::test_store 
tests/test_resources.py::test_initial_store_capacity[Store] PASSED       [ 67%]
tests/test_resources.py::test_initial_store_capacity[FilterStore] PASSED [ 68%]
tests/test_resources.py::test_store_capacity PASSED                      [ 69%]
tests/test_resources.py::test_store_cancel PASSED                        [ 69%]
tests/test_resources.py::test_priority_store_item_priority PASSED        [ 70%]
tests/test_resources.py::test_priority_store_stable_order PASSED         [ 71%]
tests/test_resources.py::test_filter_store PASSED                        [ 71%]
tests/test_resources.py::test_filter_store_get_after_mismatch 
tests/test_resources.py::test_filter_calls_best_case 
tests/test_resources.py::test_filter_calls_worst_case 
tests/test_resources.py::test_immediate_put_request 
tests/test_resources.py::test_immediate_get_request PASSED               [ 75%]
tests/test_rt.py::test_rt[0.1] PASSED                                    [ 76%]
tests/test_rt.py::test_rt[0.05] PASSED                                   [ 76%]
tests/test_rt.py::test_rt[0.15] PASSED                                   [ 77%]
tests/test_rt.py::test_rt_multiple_call PASSED                           [ 78%]
tests/test_rt.py::test_rt_slow_sim_default_behavior 
tests/test_rt.py::test_rt_slow_sim_no_error 
tests/test_rt.py::test_rt_illegal_until 
tests/test_rt.py::test_rt_sync 
tests/test_rt.py::test_run_with_untriggered_event PASSED                 [ 82%]
tests/test_timeout.py::test_discrete_time_steps PASSED                   [ 82%]
tests/test_timeout.py::test_negative_timeout PASSED                      [ 83%]
tests/test_timeout.py::test_timeout_value PASSED                         [ 84%]
tests/test_timeout.py::test_shared_timeout PASSED                        [ 84%]
tests/test_timeout.py::test_triggered_timeout PASSED                     [ 85%]
tests/test_util.py::test_start_delayed 
tests/test_util.py::test_start_delayed_error 
tests/test_util.py::test_subscribe 
tests/test_util.py::test_subscribe_terminated_proc PASSED                [ 88%]
tests/test_util.py::test_subscribe_with_join PASSED                      [ 89%]
tests/test_util.py::test_subscribe_at_timeout PASSED                     [ 89%]
tests/test_util.py::test_subscribe_at_timeout_with_value PASSED          [ 90%]
tests/test_util.py::test_all_of PASSED                                   [ 91%]
tests/test_util.py::test_all_of_generator PASSED                         [ 92%]
tests/test_util.py::test_wait_for_all_with_errors PASSED                 [ 92%]
tests/test_util.py::test_all_of_chaining 
tests/test_util.py::test_all_of_chaining_intermediate_results 
tests/test_util.py::test_all_of_with_triggered_events 
tests/test_util.py::test_any_of 
tests/test_util.py::test_any_of_with_errors PASSED                       [ 96%]
tests/test_util.py::test_any_of_chaining PASSED                          [ 97%]
tests/test_util.py::test_any_of_with_triggered_events PASSED             [ 97%]
tests/test_util.py::test_empty_any_of PASSED                             [ 98%]
tests/test_util.py::test_empty_all_of PASSED                             [ 99%]
tests/test_util.py::test_all_of_expansion PASSED                         [100%]

====================== 139 passed, 10 deselected in 2.21s ======================

PASSED                        [  0%]PASSED                [  1%]PASSED                  [  7%]PASSED                   [  7%]PASSED                    [  8%]PASSED                   [  9%]PASSED                   [ 15%]PASSED                 [ 15%]PASSED                [ 16%]PASSED                                   [ 21%]PASSED                                   [ 22%]PASSED                       [ 23%]PASSED                               [ 23%]PASSED                 [ 28%]PASSED                      [ 29%]PASSED                 [ 30%]PASSED        [ 30%]PASSED                     [ 35%]PASSED       [ 36%]PASSED                [ 37%]PASSED                         [ 43%]PASSED                          [ 43%]PASSED   [ 50%]PASSED [ 65%]PASSED [ 66%]PASSED                               [ 66%]PASSED     [ 72%]PASSED              [ 73%]PASSED             [ 74%]PASSED               [ 74%]PASSED               [ 79%]PASSED                       [ 79%]PASSED                           [ 80%]PASSED                                    [ 81%]docs create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/docs
SKIPPED: InterpreterNotFound: 
flake8 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/flake8
SKIPPED: InterpreterNotFound: 
mypy create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/mypy
SKIPPED: InterpreterNotFound: 
___________________________________ summary ____________________________________
  simpy37: commands succeeded
  simpy39: commands succeeded
SKIPPED:  docs: InterpreterNotFound: 
SKIPPED:  flake8: InterpreterNotFound: 
SKIPPED:  mypy: InterpreterNotFound: 
  congratulations :)

Process finished with exit code 0
PASSED                            [ 86%]
PASSED                      [ 87%]
PASSED                                [ 87%]
PASSED                          [ 93%]
PASSED     [ 94%]
PASSED             [ 94%]
PASSED                                   [ 95%]
```