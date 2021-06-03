# SimPy
2021-06-03

```shell
___________________________________ summary ____________________________________
  py36: commands succeeded
  py37: commands succeeded
  py38: commands succeeded
  py39: commands succeeded
  pypy3: commands succeeded
  docs: commands succeeded
  flake8: commands succeeded
  mypy: commands succeeded
  congratulations :)

Process finished with exit code 0
```

```shell
/home/cwm/git/git.c-w-m/sim_dev/.tox/sim_dev37/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 1:47 AM ...
py36 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py36
py36 installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py36 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py36 installed: attrs==21.2.0,importlib-metadata==4.4.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2,typing-extensions==3.10.0.0,zipp==3.4.1
py36 run-test-pre: PYTHONHASHSEED='2387080376'
py36 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py36/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 10001 -- --doctest-glob= tests
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

====================== 139 passed, 10 deselected in 2.26s ======================

PASSED                 [  2%]PASSED                  [  3%]PASSED              [  4%]PASSED                     [  5%]PASSED              [  5%]PASSED                  [  7%]PASSED                [ 10%]PASSED                 [ 11%]PASSED                     [ 12%]PASSED                        [ 12%]PASSED                 [ 13%]PASSED                   [ 15%]PASSED                   [ 17%]PASSED          [ 18%]PASSED        [ 19%]PASSED                                 [ 20%]PASSED                                   [ 21%]PASSED              [ 25%]PASSED       [ 25%]PASSED                   [ 26%]PASSED                  [ 27%]PASSED                 [ 28%]PASSED         [ 31%]PASSED         [ 32%]PASSED                     [ 33%]PASSED                       [ 33%]PASSED              [ 34%]PASSED                     [ 35%]PASSED                     [ 38%]PASSED                [ 38%]PASSED                    [ 39%]PASSED               [ 40%]PASSED                     [ 41%]PASSED                             [ 41%]PASSED                         [ 43%]PASSED                       [ 44%]PASSED                      [ 45%]PASSED           [ 46%]PASSED            [ 46%]PASSED                            [ 47%]PASSED                   [ 48%]PASSED            [ 48%]PASSED   [ 50%]PASSED    [ 51%]PASSED         [ 51%]PASSED               [ 52%]PASSED             [ 53%]PASSED        [ 53%]PASSED                 [ 54%]PASSED                           [ 55%]PASSED                 [ 56%]PASSED       [ 56%]PASSED                   [ 58%]PASSED                           [ 58%]PASSED                [ 59%]PASSED          [ 60%]PASSED            [ 61%]PASSED [ 61%]PASSED [ 62%]PASSED [ 63%]PASSED [ 64%]PASSED [ 65%]PASSED [ 68%]PASSED                      [ 69%]PASSED                        [ 69%]PASSED        [ 70%]PASSED         [ 71%]PASSED     [ 72%]PASSED                                    [ 76%]PASSED                                   [ 76%]PASSED                                   [ 77%]PASSED               [ 79%]PASSED                   [ 82%]PASSED                      [ 83%]PASSED                         [ 84%]PASSED                        [ 84%]py37 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py37
py37 installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py37 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py37 installed: attrs==21.2.0,importlib-metadata==4.4.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2,typing-extensions==3.10.0.0,zipp==3.4.1
PASSED                      [ 89%]PASSED                     [ 89%]PASSED          [ 90%]PASSED                                   [ 91%]PASSED                         [ 92%]PASSED                          [ 93%]PASSED                          [ 97%]PASSED             [ 97%]PASSED                             [ 98%]PASSED                             [ 99%]PASSED                         [100%]py37 run-test-pre: PYTHONHASHSEED='2387080376'
py37 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py37/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 20001 -- --doctest-glob= tests
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

====================== 139 passed, 10 deselected in 2.23s ======================

PASSED                        [  0%]PASSED                [  1%]PASSED                  [  7%]PASSED                   [  7%]PASSED                    [  8%]PASSED                   [  9%]PASSED                   [ 15%]PASSED                 [ 15%]PASSED                [ 16%]PASSED                                   [ 21%]PASSED                                   [ 22%]PASSED                       [ 23%]PASSED                               [ 23%]PASSED                 [ 28%]PASSED                      [ 29%]PASSED                 [ 30%]PASSED        [ 30%]PASSED                     [ 35%]PASSED       [ 36%]PASSED                [ 37%]PASSED                         [ 43%]PASSED                          [ 43%]PASSED   [ 50%]PASSED [ 65%]PASSED [ 66%]PASSED                               [ 66%]PASSED     [ 72%]PASSED              [ 73%]PASSED             [ 74%]PASSED               [ 74%]PASSED               [ 79%]PASSED                       [ 79%]PASSED                           [ 80%]PASSED                                    [ 81%]py38 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py38
py38 installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py38 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py38 installed: attrs==21.2.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2
PASSED                            [ 86%]PASSED                      [ 87%]PASSED                                [ 87%]PASSED                          [ 93%]PASSED     [ 94%]PASSED             [ 94%]PASSED                                   [ 95%]flake8 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/flake8
flake8 installdeps: flake8
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
flake8 installed: flake8==3.9.2,importlib-metadata==4.4.0,mccabe==0.6.1,pycodestyle==2.7.0,pyflakes==2.3.1,typing-extensions==3.10.0.0,zipp==3.4.1
mypy create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/mypy
mypy installdeps: mypy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py38 run-test-pre: PYTHONHASHSEED='2387080376'
py38 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py38/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 30001 -- --doctest-glob= tests
Launching pytest with arguments --doctest-glob= tests --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 149 items / 10 deselected / 139 selected

tests/test_condition.py::test_operator_and PASSED                        [  0%]
tests/test_condition.py::test_operator_and_blocked PASSED                [  1%]
tests/test_condition.py::test_operator_or PASSED                         [  2%]
tests/test_condition.py::test_operator_nested_and PASSED                 [  2%]
tests/test_condition.py::test_operator_nested_or PASSED                  [  3%]
tests/test_condition.py::test_nested_cond_with_error PASSED              [  4%]
tests/test_condition.py::test_cond_with_error PASSED                     [  5%]
tests/test_condition.py::test_cond_with_nested_error PASSED              [  5%]
tests/test_condition.py::test_cond_with_uncaught_error PASSED            [  6%]
tests/test_condition.py::test_iand_with_and_cond 
tests/test_condition.py::test_iand_with_or_cond PASSED                   [  7%]
tests/test_condition.py::test_ior_with_or_cond PASSED                    [  8%]
tests/test_condition.py::test_ior_with_and_cond PASSED                   [  9%]
tests/test_condition.py::test_immutable_results PASSED                   [ 10%]
tests/test_condition.py::test_shared_and_condition PASSED                [ 10%]
tests/test_condition.py::test_shared_or_condition PASSED                 [ 11%]
tests/test_condition.py::test_condition_value PASSED                     [ 12%]
tests/test_condition.py::test_result_order PASSED                        [ 12%]
tests/test_condition.py::test_nested_result_order PASSED                 [ 13%]
tests/test_condition.py::test_all_of_empty_list PASSED                   [ 14%]
tests/test_condition.py::test_any_of_empty_list 
tests/test_environment.py::test_event_queue_empty PASSED                 [ 15%]
tests/test_environment.py::test_run_negative_until PASSED                [ 16%]
tests/test_environment.py::test_run_resume PASSED                        [ 17%]
tests/test_environment.py::test_run_until_value PASSED                   [ 17%]
tests/test_environment.py::test_run_with_processed_event PASSED          [ 18%]
tests/test_environment.py::test_run_with_untriggered_event PASSED        [ 19%]
tests/test_event.py::test_succeed PASSED                                 [ 20%]
tests/test_event.py::test_fail PASSED                                    [ 20%]
tests/test_event.py::test_names 
tests/test_event.py::test_value PASSED                                   [ 22%]
tests/test_event.py::test_unavailable_value PASSED                       [ 23%]
tests/test_event.py::test_triggered PASSED                               [ 23%]
tests/test_event.py::test_callback_modification PASSED                   [ 24%]
tests/test_event.py::test_condition_callback_removal PASSED              [ 25%]
tests/test_event.py::test_condition_nested_callback_removal PASSED       [ 25%]
tests/test_exceptions.py::test_error_forwarding PASSED                   [ 26%]
tests/test_exceptions.py::test_no_parent_process PASSED                  [ 27%]
tests/test_exceptions.py::test_crashing_child_traceback PASSED           [ 28%]
tests/test_exceptions.py::test_exception_chaining 
tests/test_exceptions.py::test_invalid_event PASSED                      [ 29%]
tests/test_exceptions.py::test_exception_handling PASSED                 [ 30%]
tests/test_exceptions.py::test_callback_exception_handling PASSED        [ 30%]
tests/test_exceptions.py::test_process_exception_handling PASSED         [ 31%]
tests/test_exceptions.py::test_process_exception_chaining PASSED         [ 32%]
tests/test_exceptions.py::test_sys_excepthook PASSED                     [ 33%]
tests/test_interrupts.py::test_interruption PASSED                       [ 33%]
tests/test_interrupts.py::test_concurrent_interrupts PASSED              [ 34%]
tests/test_interrupts.py::test_concurrent_interrupts_and_events PASSED   [ 35%]
tests/test_interrupts.py::test_init_interrupt 
tests/test_interrupts.py::test_interrupt_terminated_process PASSED       [ 36%]
tests/test_interrupts.py::test_multiple_interrupts PASSED                [ 37%]
tests/test_interrupts.py::test_interrupt_self PASSED                     [ 38%]
tests/test_interrupts.py::test_immediate_interrupt PASSED                [ 38%]
tests/test_interrupts.py::test_interrupt_event PASSED                    [ 39%]
tests/test_interrupts.py::test_concurrent_behaviour PASSED               [ 40%]
tests/test_process.py::test_start_non_process PASSED                     [ 41%]
tests/test_process.py::test_get_state PASSED                             [ 41%]
tests/test_process.py::test_target PASSED                                [ 42%]
tests/test_process.py::test_wait_for_proc 
tests/test_process.py::test_return_value PASSED                          [ 43%]
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
tests/test_resources.py::test_container_init_capacity[ValueError-args6] PASSED [ 66%]
tests/test_resources.py::test_store PASSED                               [ 66%]
tests/test_resources.py::test_initial_store_capacity[Store] PASSED       [ 67%]
tests/test_resources.py::test_initial_store_capacity[FilterStore] PASSED [ 68%]
tests/test_resources.py::test_store_capacity PASSED                      [ 69%]
tests/test_resources.py::test_store_cancel PASSED                        [ 69%]
tests/test_resources.py::test_priority_store_item_priority PASSED        [ 70%]
tests/test_resources.py::test_priority_store_stable_order PASSED         [ 71%]
tests/test_resources.py::test_filter_store PASSED                        [ 71%]
tests/test_resources.py::test_filter_store_get_after_mismatch 
tests/test_resources.py::test_filter_calls_best_case PASSED              [ 73%]
tests/test_resources.py::test_filter_calls_worst_case PASSED             [ 74%]
tests/test_resources.py::test_immediate_put_request PASSED               [ 74%]
tests/test_resources.py::test_immediate_get_request PASSED               [ 75%]
tests/test_rt.py::test_rt[0.1] PASSED                                    [ 76%]
tests/test_rt.py::test_rt[0.05] PASSED                                   [ 76%]
tests/test_rt.py::test_rt[0.15] PASSED                                   [ 77%]
tests/test_rt.py::test_rt_multiple_call PASSED                           [ 78%]
tests/test_rt.py::test_rt_slow_sim_default_behavior 
tests/test_rt.py::test_rt_slow_sim_no_error PASSED                       [ 79%]
tests/test_rt.py::test_rt_illegal_until PASSED                           [ 80%]
tests/test_rt.py::test_rt_sync PASSED                                    [ 81%]
tests/test_rt.py::test_run_with_untriggered_event PASSED                 [ 82%]
tests/test_timeout.py::test_discrete_time_steps PASSED                   [ 82%]
tests/test_timeout.py::test_negative_timeout PASSED                      [ 83%]
tests/test_timeout.py::test_timeout_value PASSED                         [ 84%]
tests/test_timeout.py::test_shared_timeout PASSED                        [ 84%]
tests/test_timeout.py::test_triggered_timeout PASSED                     [ 85%]
tests/test_util.py::test_start_delayed PASSED                            [ 86%]
tests/test_util.py::test_start_delayed_error PASSED                      [ 87%]
tests/test_util.py::test_subscribe PASSED                                [ 87%]
tests/test_util.py::test_subscribe_terminated_proc PASSED                [ 88%]
tests/test_util.py::test_subscribe_with_join PASSED                      [ 89%]
tests/test_util.py::test_subscribe_at_timeout PASSED                     [ 89%]
tests/test_util.py::test_subscribe_at_timeout_with_value PASSED          [ 90%]
tests/test_util.py::test_all_of PASSED                                   [ 91%]
tests/test_util.py::test_all_of_generator PASSED                         [ 92%]
tests/test_util.py::test_wait_for_all_with_errors PASSED                 [ 92%]
tests/test_util.py::test_all_of_chaining 
tests/test_util.py::test_all_of_chaining_intermediate_results PASSED     [ 94%]
tests/test_util.py::test_all_of_with_triggered_events PASSED             [ 94%]
tests/test_util.py::test_any_of PASSED                                   [ 95%]
tests/test_util.py::test_any_of_with_errors PASSED                       [ 96%]
tests/test_util.py::test_any_of_chaining PASSED                          [ 97%]
tests/test_util.py::test_any_of_with_triggered_events PASSED             [ 97%]
tests/test_util.py::test_empty_any_of PASSED                             [ 98%]
tests/test_util.py::test_empty_all_of PASSED                             [ 99%]
tests/test_util.py::test_all_of_expansion PASSED                         [100%]

====================== 139 passed, 10 deselected in 2.19s ======================

PASSED                  [  7%]PASSED                   [ 15%]PASSED                                   [ 21%]PASSED                 [ 28%]PASSED                     [ 35%]PASSED                         [ 43%]PASSED   [ 50%]PASSED [ 65%]PASSED     [ 72%]PASSED               [ 79%]py39 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py39
py39 installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py39 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
py39 installed: attrs==21.2.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2
pypy3 create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/pypy3
pypy3 installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
pypy3 develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
pypy3 installed: attrs==21.2.0,cffi==1.14.5,greenlet==0.4.13,importlib-metadata==4.4.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,readline==6.2.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2,typing-extensions==3.10.0.0,zipp==3.4.1
docs create: /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/docs
docs installdeps: pytest, pytest-benchmark
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
docs develop-inst: /home/cwm/git/git.c-w-m/sim_dev/src/simpy
WARNING: Discarding $PYTHONPATH from environment, to override specify PYTHONPATH in 'passenv' in your configuration.
docs installed: attrs==21.2.0,importlib-metadata==4.4.0,iniconfig==1.1.1,packaging==20.9,pluggy==0.13.1,py==1.10.0,py-cpuinfo==8.0.0,pyparsing==2.4.7,pytest==6.2.4,pytest-benchmark==3.4.1,-e git+https://github.com/c-w-m/simpy.git@b2d7374dd930bf2a8019fb03291f9a20faf5932c#egg=simpy&subdirectory=../../../src/simpy,toml==0.10.2,typing-extensions==3.10.0.0,zipp==3.4.1
PASSED                          [ 93%]py39 run-test-pre: PYTHONHASHSEED='2387080376'
py39 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/py39/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 40001 -- --doctest-glob= tests
Launching pytest with arguments --doctest-glob= tests --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 149 items / 10 deselected / 139 selected

tests/test_condition.py::test_operator_and PASSED                        [  0%]
tests/test_condition.py::test_operator_and_blocked PASSED                [  1%]
tests/test_condition.py::test_operator_or PASSED                         [  2%]
tests/test_condition.py::test_operator_nested_and PASSED                 [  2%]
tests/test_condition.py::test_operator_nested_or PASSED                  [  3%]
tests/test_condition.py::test_nested_cond_with_error PASSED              [  4%]
tests/test_condition.py::test_cond_with_error 
tests/test_condition.py::test_cond_with_nested_error PASSED              [  5%]
tests/test_condition.py::test_cond_with_uncaught_error PASSED            [  6%]
tests/test_condition.py::test_iand_with_and_cond 
tests/test_condition.py::test_iand_with_or_cond 
tests/test_condition.py::test_ior_with_or_cond PASSED                    [  8%]
tests/test_condition.py::test_ior_with_and_cond PASSED                   [  9%]
tests/test_condition.py::test_immutable_results PASSED                   [ 10%]
tests/test_condition.py::test_shared_and_condition PASSED                [ 10%]
tests/test_condition.py::test_shared_or_condition PASSED                 [ 11%]
tests/test_condition.py::test_condition_value 
tests/test_condition.py::test_result_order 
tests/test_condition.py::test_nested_result_order PASSED                 [ 13%]
tests/test_condition.py::test_all_of_empty_list PASSED                   [ 14%]
tests/test_condition.py::test_any_of_empty_list 
tests/test_environment.py::test_event_queue_empty PASSED                 [ 15%]
tests/test_environment.py::test_run_negative_until PASSED                [ 16%]
tests/test_environment.py::test_run_resume PASSED                        [ 17%]
tests/test_environment.py::test_run_until_value PASSED                   [ 17%]
tests/test_environment.py::test_run_with_processed_event 
tests/test_environment.py::test_run_with_untriggered_event 
tests/test_event.py::test_succeed PASSED                                 [ 20%]
tests/test_event.py::test_fail PASSED                                    [ 20%]
tests/test_event.py::test_names 
tests/test_event.py::test_value 
tests/test_event.py::test_unavailable_value PASSED                       [ 23%]
tests/test_event.py::test_triggered PASSED                               [ 23%]
tests/test_event.py::test_callback_modification PASSED                   [ 24%]
tests/test_event.py::test_condition_callback_removal 
tests/test_event.py::test_condition_nested_callback_removal 
tests/test_exceptions.py::test_error_forwarding 
tests/test_exceptions.py::test_no_parent_process PASSED                  [ 27%]
tests/test_exceptions.py::test_crashing_child_traceback PASSED           [ 28%]
tests/test_exceptions.py::test_exception_chaining 
tests/test_exceptions.py::test_invalid_event 
tests/test_exceptions.py::test_exception_handling PASSED                 [ 30%]
tests/test_exceptions.py::test_callback_exception_handling PASSED        [ 30%]
tests/test_exceptions.py::test_process_exception_handling PASSED         [ 31%]
tests/test_exceptions.py::test_process_exception_chaining 
tests/test_exceptions.py::test_sys_excepthook 
tests/test_interrupts.py::test_interruption 
tests/test_interrupts.py::test_concurrent_interrupts PASSED              [ 34%]
tests/test_interrupts.py::test_concurrent_interrupts_and_events PASSED   [ 35%]
tests/test_interrupts.py::test_init_interrupt 
tests/test_interrupts.py::test_interrupt_terminated_process 
tests/test_interrupts.py::test_multiple_interrupts PASSED                [ 37%]
tests/test_interrupts.py::test_interrupt_self PASSED                     [ 38%]
tests/test_interrupts.py::test_immediate_interrupt PASSED                [ 38%]
tests/test_interrupts.py::test_interrupt_event 
tests/test_interrupts.py::test_concurrent_behaviour 
tests/test_process.py::test_start_non_process 
tests/test_process.py::test_get_state PASSED                             [ 41%]
tests/test_process.py::test_target PASSED                                [ 42%]
tests/test_process.py::test_wait_for_proc 
tests/test_process.py::test_return_value 
tests/test_process.py::test_child_exception PASSED                       [ 44%]
tests/test_process.py::test_interrupted_join PASSED                      [ 45%]
tests/test_process.py::test_interrupted_join_and_rejoin PASSED           [ 46%]
tests/test_process.py::test_error_and_interrupted_join 
tests/test_resources.py::test_resource 
tests/test_resources.py::test_resource_capacity 
tests/test_resources.py::test_resource_context_manager PASSED            [ 48%]
tests/test_resources.py::test_resource_slots PASSED                      [ 49%]
tests/test_resources.py::test_resource_continue_after_interrupt 
tests/test_resources.py::test_resource_release_after_interrupt PASSED    [ 51%]
tests/test_resources.py::test_resource_immediate_requests PASSED         [ 51%]
tests/test_resources.py::test_resource_cm_exception PASSED               [ 52%]
tests/test_resources.py::test_resource_with_condition PASSED             [ 53%]
tests/test_resources.py::test_resource_with_priority_queue 
tests/test_resources.py::test_sorted_queue_maxlen 
tests/test_resources.py::test_get_users 
tests/test_resources.py::test_preemptive_resource 
tests/test_resources.py::test_preemptive_resource_timeout_0 PASSED       [ 56%]
tests/test_resources.py::test_mixed_preemption PASSED                    [ 57%]
tests/test_resources.py::test_nested_preemption PASSED                   [ 58%]
tests/test_resources.py::test_container PASSED                           [ 58%]
tests/test_resources.py::test_container_get_queued PASSED                [ 59%]
tests/test_resources.py::test_initial_container_capacity PASSED          [ 60%]
tests/test_resources.py::test_container_get_put_bounds PASSED            [ 61%]
tests/test_resources.py::test_container_init_capacity[None-args0] 
tests/test_resources.py::test_container_init_capacity[None-args1] 
tests/test_resources.py::test_container_init_capacity[None-args2] 
tests/test_resources.py::test_container_init_capacity[ValueError-args3] PASSED [ 64%]
tests/test_resources.py::test_container_init_capacity[ValueError-args4] PASSED [ 64%]
tests/test_resources.py::test_container_init_capacity[ValueError-args5] 
tests/test_resources.py::test_container_init_capacity[ValueError-args6] 
tests/test_resources.py::test_store PASSED                               [ 66%]
tests/test_resources.py::test_initial_store_capacity[Store] PASSED       [ 67%]
tests/test_resources.py::test_initial_store_capacity[FilterStore] PASSED [ 68%]
tests/test_resources.py::test_store_capacity PASSED                      [ 69%]
tests/test_resources.py::test_store_cancel PASSED                        [ 69%]
tests/test_resources.py::test_priority_store_item_priority PASSED        [ 70%]
tests/test_resources.py::test_priority_store_stable_order PASSED         [ 71%]
tests/test_resources.py::test_filter_store PASSED                        [ 71%]
tests/test_resources.py::test_filter_store_get_after_mismatch 
tests/test_resources.py::test_filter_calls_best_case 
tests/test_resources.py::test_filter_calls_worst_case PASSED             [ 74%]
tests/test_resources.py::test_immediate_put_request PASSED               [ 74%]
tests/test_resources.py::test_immediate_get_request PASSED               [ 75%]
tests/test_rt.py::test_rt[0.1] PASSED                                    [ 76%]
tests/test_rt.py::test_rt[0.05] 
tests/test_rt.py::test_rt[0.15] PASSED                                   [ 77%]
tests/test_rt.py::test_rt_multiple_call PASSED                           [ 78%]
tests/test_rt.py::test_rt_slow_sim_default_behavior 
tests/test_rt.py::test_rt_slow_sim_no_error 
tests/test_rt.py::test_rt_illegal_until PASSED                           [ 80%]
tests/test_rt.py::test_rt_sync PASSED                                    [ 81%]
tests/test_rt.py::test_run_with_untriggered_event PASSED                 [ 82%]
tests/test_timeout.py::test_discrete_time_steps PASSED                   [ 82%]
tests/test_timeout.py::test_negative_timeout 
tests/test_timeout.py::test_timeout_value 
tests/test_timeout.py::test_shared_timeout PASSED                        [ 84%]
tests/test_timeout.py::test_triggered_timeout PASSED                     [ 85%]
tests/test_util.py::test_start_delayed 
tests/test_util.py::test_start_delayed_error PASSED                      [ 87%]
tests/test_util.py::test_subscribe PASSED                                [ 87%]
tests/test_util.py::test_subscribe_terminated_proc PASSED                [ 88%]
tests/test_util.py::test_subscribe_with_join PASSED                      [ 89%]
tests/test_util.py::test_subscribe_at_timeout 
tests/test_util.py::test_subscribe_at_timeout_with_value 
tests/test_util.py::test_all_of 
tests/test_util.py::test_all_of_generator PASSED                         [ 92%]
tests/test_util.py::test_wait_for_all_with_errors PASSED                 [ 92%]
tests/test_util.py::test_all_of_chaining 
tests/test_util.py::test_all_of_chaining_intermediate_results 
tests/test_util.py::test_all_of_with_triggered_events PASSED             [ 94%]
tests/test_util.py::test_any_of PASSED                                   [ 95%]
tests/test_util.py::test_any_of_with_errors PASSED                       [ 96%]
tests/test_util.py::test_any_of_chaining 
tests/test_util.py::test_any_of_with_triggered_events 
tests/test_util.py::test_empty_any_of 
tests/test_util.py::test_empty_all_of 
tests/test_util.py::test_all_of_expansion PASSED                         [100%]

====================== 139 passed, 10 deselected in 2.30s ======================

PASSED                     [  5%]PASSED                  [  7%]PASSED                   [  7%]PASSED                     [ 12%]PASSED                        [ 12%]PASSED                   [ 15%]PASSED          [ 18%]PASSED        [ 19%]PASSED                                   [ 21%]PASSED                                   [ 22%]PASSED              [ 25%]PASSED       [ 25%]PASSED                   [ 26%]PASSED                 [ 28%]PASSED                      [ 29%]PASSED         [ 32%]PASSED                     [ 33%]PASSED                       [ 33%]PASSED                     [ 35%]PASSED       [ 36%]PASSED                    [ 39%]PASSED               [ 40%]PASSED                     [ 41%]PASSED                         [ 43%]PASSED                          [ 43%]PASSED            [ 46%]PASSED                            [ 47%]PASSED                   [ 48%]PASSED   [ 50%]PASSED        [ 53%]PASSED                 [ 54%]PASSED                           [ 55%]PASSED                 [ 56%]PASSED [ 61%]PASSED [ 62%]PASSED [ 63%]PASSED [ 65%]PASSED [ 66%]PASSED     [ 72%]PASSED              [ 73%]PASSED                                   [ 76%]PASSED               [ 79%]PASSED                       [ 79%]PASSED                      [ 83%]PASSED                         [ 84%]PASSED                            [ 86%]PASSED                     [ 89%]PASSED          [ 90%]PASSED                                   [ 91%]PASSED                          [ 93%]PASSED     [ 94%]PASSED                          [ 97%]PASSED             [ 97%]PASSED                             [ 98%]PASSED                             [ 99%]pypy3 run-test-pre: PYTHONHASHSEED='2387080376'
pypy3 run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/pypy3/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 50001 -- --doctest-glob= tests
Launching pytest with arguments --doctest-glob= tests --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 149 items / 10 deselected / 139 selected

tests/test_condition.py::test_operator_and PASSED                        [  0%]
tests/test_condition.py::test_operator_and_blocked PASSED                [  1%]
tests/test_condition.py::test_operator_or PASSED                         [  2%]
tests/test_condition.py::test_operator_nested_and PASSED                 [  2%]
tests/test_condition.py::test_operator_nested_or PASSED                  [  3%]
tests/test_condition.py::test_nested_cond_with_error PASSED              [  4%]
tests/test_condition.py::test_cond_with_error 
tests/test_condition.py::test_cond_with_nested_error 
tests/test_condition.py::test_cond_with_uncaught_error PASSED            [  6%]
tests/test_condition.py::test_iand_with_and_cond 
tests/test_condition.py::test_iand_with_or_cond PASSED                   [  7%]
tests/test_condition.py::test_ior_with_or_cond PASSED                    [  8%]
tests/test_condition.py::test_ior_with_and_cond PASSED                   [  9%]
tests/test_condition.py::test_immutable_results PASSED                   [ 10%]
tests/test_condition.py::test_shared_and_condition PASSED                [ 10%]
tests/test_condition.py::test_shared_or_condition PASSED                 [ 11%]
tests/test_condition.py::test_condition_value 
tests/test_condition.py::test_result_order 
tests/test_condition.py::test_nested_result_order 
tests/test_condition.py::test_all_of_empty_list PASSED                   [ 14%]
tests/test_condition.py::test_any_of_empty_list 
tests/test_environment.py::test_event_queue_empty PASSED                 [ 15%]
tests/test_environment.py::test_run_negative_until PASSED                [ 16%]
tests/test_environment.py::test_run_resume PASSED                        [ 17%]
tests/test_environment.py::test_run_until_value PASSED                   [ 17%]
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
tests/test_interrupts.py::test_interrupt_self PASSED                     [ 38%]
tests/test_interrupts.py::test_immediate_interrupt 
tests/test_interrupts.py::test_interrupt_event 
tests/test_interrupts.py::test_concurrent_behaviour 
tests/test_process.py::test_start_non_process 
tests/test_process.py::test_get_state 
tests/test_process.py::test_target PASSED                                [ 42%]
tests/test_process.py::test_wait_for_proc 
tests/test_process.py::test_return_value PASSED                          [ 43%]
tests/test_process.py::test_child_exception PASSED                       [ 44%]
tests/test_process.py::test_interrupted_join PASSED                      [ 45%]
tests/test_process.py::test_interrupted_join_and_rejoin 
tests/test_process.py::test_error_and_interrupted_join 
tests/test_resources.py::test_resource 
tests/test_resources.py::test_resource_capacity 
tests/test_resources.py::test_resource_context_manager 
tests/test_resources.py::test_resource_slots PASSED                      [ 49%]
tests/test_resources.py::test_resource_continue_after_interrupt 
tests/test_resources.py::test_resource_release_after_interrupt PASSED    [ 51%]
tests/test_resources.py::test_resource_immediate_requests PASSED         [ 51%]
tests/test_resources.py::test_resource_cm_exception PASSED               [ 52%]
tests/test_resources.py::test_resource_with_condition 
tests/test_resources.py::test_resource_with_priority_queue 
tests/test_resources.py::test_sorted_queue_maxlen 
tests/test_resources.py::test_get_users 
tests/test_resources.py::test_preemptive_resource 
tests/test_resources.py::test_preemptive_resource_timeout_0 
tests/test_resources.py::test_mixed_preemption PASSED                    [ 57%]
tests/test_resources.py::test_nested_preemption PASSED                   [ 58%]
tests/test_resources.py::test_container PASSED                           [ 58%]
tests/test_resources.py::test_container_get_queued PASSED                [ 59%]
tests/test_resources.py::test_initial_container_capacity PASSED          [ 60%]
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
tests/test_resources.py::test_initial_store_capacity[FilterStore] PASSED [ 68%]
tests/test_resources.py::test_store_capacity PASSED                      [ 69%]
tests/test_resources.py::test_store_cancel PASSED                        [ 69%]
tests/test_resources.py::test_priority_store_item_priority PASSED        [ 70%]
tests/test_resources.py::test_priority_store_stable_order 
tests/test_resources.py::test_filter_store PASSED                        [ 71%]
tests/test_resources.py::test_filter_store_get_after_mismatch 
tests/test_resources.py::test_filter_calls_best_case PASSED              [ 73%]
tests/test_resources.py::test_filter_calls_worst_case PASSED             [ 74%]
tests/test_resources.py::test_immediate_put_request PASSED               [ 74%]
tests/test_resources.py::test_immediate_get_request PASSED               [ 75%]
tests/test_rt.py::test_rt[0.1] PASSED                                    [ 76%]
tests/test_rt.py::test_rt[0.05] 
tests/test_rt.py::test_rt[0.15] 
tests/test_rt.py::test_rt_multiple_call PASSED                           [ 78%]
tests/test_rt.py::test_rt_slow_sim_default_behavior 
tests/test_rt.py::test_rt_slow_sim_no_error PASSED                       [ 79%]
tests/test_rt.py::test_rt_illegal_until PASSED                           [ 80%]
tests/test_rt.py::test_rt_sync PASSED                                    [ 81%]
tests/test_rt.py::test_run_with_untriggered_event PASSED                 [ 82%]
tests/test_timeout.py::test_discrete_time_steps PASSED                   [ 82%]
tests/test_timeout.py::test_negative_timeout 
tests/test_timeout.py::test_timeout_value 
tests/test_timeout.py::test_shared_timeout 
tests/test_timeout.py::test_triggered_timeout PASSED                     [ 85%]
tests/test_util.py::test_start_delayed PASSED                            [ 86%]
tests/test_util.py::test_start_delayed_error PASSED                      [ 87%]
tests/test_util.py::test_subscribe PASSED                                [ 87%]
tests/test_util.py::test_subscribe_terminated_proc PASSED                [ 88%]
tests/test_util.py::test_subscribe_with_join PASSED                      [ 89%]
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

====================== 139 passed, 10 deselected in 5.44s ======================

PASSED                     [  5%]PASSED              [  5%]PASSED                  [  7%]PASSED                     [ 12%]PASSED                        [ 12%]PASSED                 [ 13%]PASSED                   [ 15%]PASSED          [ 18%]PASSED        [ 19%]PASSED                                 [ 20%]PASSED                                   [ 21%]PASSED              [ 25%]PASSED       [ 25%]PASSED                   [ 26%]PASSED                  [ 27%]PASSED                 [ 28%]PASSED         [ 31%]PASSED         [ 32%]PASSED                     [ 33%]PASSED                       [ 33%]PASSED              [ 34%]PASSED                     [ 35%]PASSED                [ 38%]PASSED                    [ 39%]PASSED               [ 40%]PASSED                     [ 41%]PASSED                             [ 41%]PASSED                         [ 43%]PASSED           [ 46%]PASSED            [ 46%]PASSED                            [ 47%]PASSED                   [ 48%]PASSED            [ 48%]PASSED   [ 50%]PASSED             [ 53%]PASSED        [ 53%]PASSED                 [ 54%]PASSED                           [ 55%]PASSED                 [ 56%]PASSED       [ 56%]PASSED            [ 61%]PASSED [ 61%]PASSED [ 62%]PASSED [ 63%]PASSED [ 64%]PASSED [ 65%]PASSED         [ 71%]PASSED     [ 72%]PASSED                                   [ 76%]PASSED                                   [ 77%]PASSED               [ 79%]PASSED                      [ 83%]PASSED                         [ 84%]PASSED                        [ 84%]PASSED                     [ 89%]PASSED          [ 90%]PASSED                                   [ 91%]PASSED                         [ 92%]PASSED                          [ 93%]PASSED                          [ 97%]PASSED             [ 97%]PASSED                             [ 98%]PASSED                             [ 99%]PASSED                         [100%]docs run-test-pre: PYTHONHASHSEED='2387080376'
docs run-test: commands[0] | /home/cwm/git/git.c-w-m/sim_dev/src/simpy/.tox/docs/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --offset 60001 -- '--doctest-glob=*.rst' --doctest-glob=README.rst README.rst docs/
Launching pytest with arguments --doctest-glob=*.rst --doctest-glob=README.rst README.rst docs/ --no-header --no-summary -q in /home/cwm/git/git.c-w-m/sim_dev/src/simpy

============================= test session starts ==============================
collecting ... collected 19 items

README.rst::README.rst 
docs/index.rst::index.rst PASSED                                            [  5%]
docs/examples/code/bank_renege.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/bank_renege.py PASSED [ 15%]
docs/examples/code/carwash.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/carwash.py PASSED [ 21%]
docs/examples/code/gas_station_refuel.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/gas_station_refuel.py 
docs/examples/code/latency.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/latency.py PASSED [ 31%]
docs/examples/code/machine_shop.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/machine_shop.py PASSED [ 36%]
docs/examples/code/movie_renege.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/movie_renege.py PASSED [ 42%]
docs/examples/code/process_communication.py::/home/cwm/git/git.c-w-m/sim_dev/src/simpy/docs/examples/code/process_communication.py PASSED [ 47%]
docs/simpy_intro/basic_concepts.rst::basic_concepts.rst 
docs/simpy_intro/process_interaction.rst::process_interaction.rst 
docs/simpy_intro/shared_resources.rst::shared_resources.rst 
docs/topical_guides/environments.rst::environments.rst PASSED            [ 68%]
docs/topical_guides/events.rst::events.rst PASSED                        [ 73%]
docs/topical_guides/monitoring.rst::monitoring.rst 
docs/topical_guides/process_interaction.rst::process_interaction.rst 
docs/topical_guides/real-time-simulations.rst::real-time-simulations.rst 
docs/topical_guides/resources.rst::resources.rst 
docs/topical_guides/simpy_basics.rst::simpy_basics.rst PASSED            [100%]

============================== 19 passed in 2.04s ==============================

PASSED                                         [ 10%]PASSED [ 26%]PASSED           [ 52%]PASSED [ 57%]PASSED       [ 63%]PASSED                [ 78%]PASSED [ 84%]PASSED [ 89%]PASSED                  [ 94%]Exception ignored in: <generator object Car.run at 0x7fe8503c0550>
Traceback (most recent call last):
  File "<doctest process_interaction.rst[6]>", line 13, in run
NameError: name 'simpy' is not defined
flake8 run-test-pre: PYTHONHASHSEED='2387080376'
flake8 run-test: commands[0] | flake8

mypy installed: mypy==0.812,mypy-extensions==0.4.3,typed-ast==1.4.3,typing-extensions==3.10.0.0
mypy run-test-pre: PYTHONHASHSEED='2387080376'
mypy run-test: commands[0] | mypy --pretty
Success: no issues found in 11 source files

___________________________________ summary ____________________________________
  py36: commands succeeded
  py37: commands succeeded
  py38: commands succeeded
  py39: commands succeeded
  pypy3: commands succeeded
  docs: commands succeeded
  flake8: commands succeeded
  mypy: commands succeeded
  congratulations :)

Process finished with exit code 0

```