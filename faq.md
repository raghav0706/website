---
layout: default
---

{{tag>faq}}

# Frequently Asked Questions

On this page you can find (and add) answers to a variety of Fieldtrip-related questions.

We invite you to [add your own](/contribute) example scripts or frequently asked questions on the wiki. Also tutorials can be added. Every time you explain somebody something about Fieldtrip, please consider whether you could use the wiki for this so others can learn from it as well.

See also the [tutorials](/tutorial) and [example scripts](/example).

##  Reading and preprocessing data

*  [How can I consistently represent artifacts in my data?](/faq/how_can_i_consistently_represent_artifacts_in_my_data)
*  [How can I convert one dataformat into an other?](/faq/how_can_i_convert_one_dataformat_into_an_other)
*  [How can I find out what eventvalues and eventtypes there are in my data?](/faq/how_can_i_find_out_what_eventvalues_and_eventtypes_there_are_in_my_data)
*  [How can I import my own dataformat?](/faq/how_can_i_import_my_own_dataformat)
*  [How can I inspect the electrode impedances of my data?](/faq/how_can_i_inspect_the_electrode_impedances_of_my_data)
*  [How can I interpret the different types of padding that I find when dealing with artifacts?](/faq/how_can_i_interpret_the_different_types_of_padding_that_i_find_when_dealing_with_artifacts)
*  [How can I merge two datasets that were acquired simultaneously with different amplifiers?](/faq/how_can_i_merge_two_datasets_that_were_acquired_simultaneously_with_different_amplifiers)
*  [How can I preprocess a dataset that is too large to fit into memory?](/faq/how_can_i_preprocess_a_dataset_that_is_too_large_to_fit_into_memory)
*  [How can I process continuous data without triggers?](/faq/how_can_i_process_continuous_data_without_triggers)
*  [How can I read EGI mff data without the JVM?](/faq/how_can_i_read_egi_mff_data_without_the_jvm)
*  [How can I read all channels from an EDF file that contains multiple sampling rates?](/faq/how_can_i_read_all_channels_from_an_edf_file_that_contains_multiple_sampling_rates)
*  [How can I transform trigger values from bits to decimal representation with a trialfun?](/faq/how_can_i_transform_trigger_values_from_bits_to_decimal_representation_with_a_trialfun)
*  [How can I use the databrowser?](/faq/how_can_i_use_the_databrowser)
*  [How can extend the reading functions with a new dataformat?](/faq/how_can_extend_the_reading_functions_with_a_new_dataformat)
*  [How does the CTF higher-order gradiometer work?](/faq/how_does_the_ctf_higher-order_gradiometer_work)
*  [How does the filter padding in preprocessing work?](/faq/how_does_the_filter_padding_in_preprocessing_work)
*  [I have problems reading in neuroscan .cnt files. How can I fix this?](/faq/i_have_problems_reading_in_neuroscan_.cnt_files._how_can_i_fix_this)
*  [I used ICA on my MEG data from before 2012 and now fieldtrip crashes, why is that?](/faq/i_used_ica_on_my_meg_data_from_before_2012_and_now_fieldtrip_crashes,_why_is_that)
*  [I used to work with trl-matrices that have more than 3 columns. Why is this not supported anymore?](/faq/i_used_to_work_with_trl-matrices_that_have_more_than_3_columns._why_is_this_not_supported_anymore)
*  [Is it possible to keep track of trial-specific information in my FieldTrip analysis pipeline?](/faq/is_it_possible_to_keep_track_of_trial-specific_information_in_my_fieldtrip_analysis_pipeline)
*  [Reading is slow, can I write my raw data to a more efficient file format?](/faq/reading_is_slow,_can_i_write_my_raw_data_to_a_more_efficient_file_format)
*  [The databrowser crashes and destroys the whole MATLAB session, how can I resolve this?](/faq/the_databrowser_crashes_and_destroys_the_whole_matlab_session,_how_can_i_resolve_this)
*  [What kind of dataformats can I read in?](/faq/what_kind_of_dataformats_can_i_read_in)
*  [What kind of filters can I apply to my data?](/faq/what_kind_of_filters_can_i_apply_to_my_data)
*  [Why are the fileio functions stateless, does the fseek not make them very slow?](/faq/why_are_the_fileio_functions_stateless,_does_the_fseek_not_make_them_very_slow)
*  [Why is there a residual 50Hz line-noise component after applying a DFT filter?](/faq/why_is_there_a_residual_50hz_line-noise_component_after_applying_a_dft_filter)
*  [How can I check or decipher the sequence of triggers in my data?](/faq/triggers)

##  Spectral analysis
*  [Why does my TFR contain NaNs?](/faq/why_does_my_tfr_contain_nans)
*  [Why does my TFR look strange (part I, demeaning)?](/faq/why_does_my_tfr_look_strange)
*  [Why does my TFR look strange (part II, detrending)?](/faq/why_does_my_tfr_look_strange_part_ii)
*  [What does "padding not sufficient for requested frequency resolution" mean?](/faq/what_does_"padding_not_sufficient_for_requested_frequency_resolution"_mean)
*  [Why does my output.freq not match my cfg.foi when using 'mtmconvol' in ft_freqanalyis?](/faq/why_does_my_output.freq_not_match_my_cfg.foi_when_using_mtmconvol_in_ft_freqanalyis)
*  [Why does my output.freq not match my cfg.foi when using 'wavelet' (formerly 'wltconvol') in ft_freqanalyis?](/faq/why_does_my_output.freq_not_match_my_cfg.foi_when_using_wavelet_formerly_wltconvol_in_ft_freqanalyis)
*  [What convention is used to define absolute phase in 'mtmconvol', 'wavelet' and 'mtmfft'](/faq/what_convention_is_used_to_define_absolute_phase_in_mtmconvol_wavelet_and_mtmfft)
*  [In what way can frequency domain data be represented in FieldTrip?](/faq/in_what_way_can_frequency_domain_data_be_represented_in_fieldtrip)
*  [What is the difference between coherence and coherency?](/faq/what_is_the_difference_between_coherence_and_coherency)
*  [How can I do time-frequency analysis on continuous data?](/faq/how_can_i_do_time-frequency_analysis_on_continuous_data)
*  [How can I compute inter-trial coherence?](/faq/itc)
*  [Why am I not getting exact integer frequencies?](/faq/why_am_i_not_getting_exact_integer_frequencies)
*  [How does mtmconvol work?](/faq/mtmconvol)

##  Source reconstruction
*  [Can I do combined EEG and MEG source reconstruction?](/faq/can_i_do_combined_eeg_and_meg_source_reconstruction)
*  [Can I restrict the source reconstruction to the grey matter?](/faq/can_i_restrict_the_source_reconstruction_to_the_grey_matter)
*  [How are electrodes, magnetometers or gradiometers described?](/faq/how_are_electrodes,_magnetometers_or_gradiometers_described)
*  [Should I use a Polhemus or a Structure Sensor to record electrode positions?](/faq/structuresensor)
*  [How are the LPA and RPA points defined?](/faq/how_are_the_lpa_and_rpa_points_defined)
*  [How are the different head and MRI coordinate systems defined?](/faq/how_are_the_different_head_and_mri_coordinate_systems_defined)
*  [How can I check whether the grid that I have is aligned to the segmented volume and to the sensor gradiometer?](/faq/how_can_i_check_whether_the_grid_that_i_have_is_aligned_to_the_segmented_volume_and_to_the_sensor_gradiometer)
*  [How can I convert an anatomical mri from DICOM into CTF format?](/faq/how_can_i_convert_an_anatomical_mri_from_dicom_into_ctf_format)
*  [How can I determine the anatomical label of a source?](/faq/how_can_i_determine_the_anatomical_label_of_a_source)
*  [How can I fine-tune my BEM volume conduction model?](/faq/how_can_i_fine-tune_my_bem_volume_conduction_model)
*  [How can I map source locations onto an anatomical label in an atlas?](/faq/how_can_i_map_source_locations_between_two_different_representations)
*  [How can I use OpenMEEG for forward modelling?](/faq/how_can_i_use_openmeeg_for_forward_modelling)
*  [How can I visualize the different geometrical objects that are needed for forward and inverse computations?](/faq/how_can_i_visualize_the_different_geometrical_objects_that_are_needed_for_forward_and_inverse_computations)
*  [How do I install the OpenMEEG binaries?](/faq/how_do_i_install_the_openmeeg_binaries)
*  [How is anatomical, functional or statistical "volume data" described?](/faq/how_is_anatomical,_functional_or_statistical_"volume_data"_described)
*  [How to coregister an anatomical MRI with the gradiometer or electrode positions?](/faq/how_to_coregister_an_anatomical_mri_with_the_gradiometer_or_electrode_positions)
*  [Is it good or bad to have dipole locations outside of the brain for which the source reconstruction is computed?](/faq/is_it_good_or_bad_to_have_dipole_locations_outside_of_the_brain_for_which_the_source_reconstruction_is_computed)
*  [Is it important to have accurate measurements of electrode locations for EEG source reconstruction?](/faq/is_it_important_to_have_accurate_measurements_of_electrode_locations_for_eeg_source_reconstruction)
*  [My MRI is upside down, is this a problem?](/faq/my_mri_is_upside_down,_is_this_a_problem)
*  [What is the conductivity of the brain, CSF, skull and skin tissue?](/faq/what_is_the_conductivity_of_the_brain,_csf,_skull_and_skin_tissue)
*  [What kind of volume conduction models are implemented?](/faq/what_kind_of_volume_conduction_models_are_implemented)
*  [Where can I find the dipoli command-line executable?](/faq/where_can_i_find_the_dipoli_command-line_executable)
*  [Why is there a rim around the brain for which the source reconstruction is not computed?](/faq/why_is_there_a_rim_around_the_brain_for_which_the_source_reconstruction_is_not_computed)
*  [Why should I use an average reference for EEG source reconstruction?](/faq/why_should_i_use_an_average_reference_for_eeg_source_reconstruction)
*  [What is the difference between the ACPC, MNI, SPM and TAL coordinate systems?](/faq/acpc)
*  [Where is the anterior commissure?](/faq/anterior_commissure_)
*  [How should I specify the fiducials?](/faq/fiducial)
*  [How do homogenous coordinate transformation matrices work?](/faq/homogenous)
*  [How to change the MRI orientation, the voxel size or the field-of-view?](/faq/how_change_mri_orientation_size_fov)

##  Statistical analysis
*  [How NOT to interpret results from a cluster-based permutation test?](/faq/how_not_to_interpret_results_from_a_cluster-based_permutation_test)
*  [Why should I use the cfg.correcttail option when using statistics_montecarlo?](/faq/why_should_i_use_the_cfg.correcttail_option_when_using_statistics_montecarlo)
*  [What is the idea behind statistical inference at the second-level?](/faq/what_is_the_idea_behind_statistical_inference_at_the_second-level)
*  [How can I use the ivar, uvar, wvar and cvar options to precisely control the permutations?](/faq/how_can_i_use_the_ivar,_uvar,_wvar_and_cvar_options_to_precisely_control_the_permutations)
*  [How can I define neighbouring sensors?](/faq/how_can_i_define_neighbouring_sensors)
*  [How does ft_prepare_neighbours work?](/faq/how_does_ft_prepare_neighbours_work)
*  [How can I define my own neighbourhood template?](/faq/how_can_i_define_my_own_neighbourhood_template)
*  [Why are there multiple neighbour templates for the NeuroMag306 system?](/faq/why_are_there_multiple_neighbour_templates_for_the_neuromag306_system)
*  [How can I test an interaction effect using cluster-based permutation tests?](/faq/how_can_i_test_an_interaction_effect_using_cluster-based_permutation_tests)
*  [How can I determine the onset of an effect?](/faq/how_can_i_determine_the_onset_of_an_effect)
*  [How can I test for correlations between neuronal data and quantitative stimulus and behavioural variables?](/faq/how_can_i_test_for_correlations_between_neuronal_data_and_quantitative_stimulus_and_behavioural_variables)

## Plotting and visualization
*  [Why does my anatomical MRI show upside-down when plotting it with ft_sourceplot?](/faq/why_does_my_anatomical_mri_show_upside-down_when_plotting_it_with_ft_sourceplot)
*  [What is the plotting convention for anatomical MRIs?](/faq/what_is_the_plotting_convention_for_anatomical_mris)
*  [How can I visualize a 'localspheres' volume conductor model?](/faq/how_can_i_visualize_a_'localspheres'_volume_conductor_model)
*  [I am having problems printing figures that use opacity](/faq/i_am_having_problems_printing_figures_that_use_opacity)
*  [I am getting strange artifacts in figures that use opacity](/faq/i_am_getting_strange_artifacts_in_figures_that_use_opacity)
*  [What is a good way to save images for later processing in other software?](/faq/what_is_a_good_way_to_save_images_for_later_processing_in_other_software)
*  [What is the format of the layout file, which is used for plotting?](/faq/what_is_the_format_of_the_layout_file,_which_is_used_for_plotting)
*  [How do I construct a layout file for the plotting functions?](/faq/how_do_i_construct_a_layout_file_for_the_plotting_functions)
*  [What are the different Neuromag and Yokogawa layouts good for?](/faq/what_are_the_different_neuromag_and_yokogawa_layouts_good_for)
*  [How can I play back EEG/MEG and synchronous audio or video?](/faq/audiovideo)

##  Experimental questions
*  [How can I use my MacBook Pro for stimulus presentation in the MEG lab?](/faq/how_can_i_use_my_macbook_pro_for_stimulus_presentation_in_the_meg_lab)
*  [How can I check the quality of an MEEG dataset?](/faq/how_can_i_check_the_quality_of_an_meeg_dataset)
*  [How can I monitor a subject's head position during a MEG session?](/faq/how_can_i_monitor_a_subject's_head_position_during_a_meg_session)
*  [How can I visualize the Neuromag head position indicator coils?](/faq/how_can_i_visualize_the_neuromag_head_position_indicator_coils)
*  [How can I change the head localization in a CTF dataset?](/faq/how_can_i_change_the_head_localization_in_a_ctf_dataset)
*  [How can I test the serial port connection between two computers?](/faq/how_can_i_test_the_serial_port_connection_between_two_computers)

##  Realtime data streaming and analysis
*  [How fast is the FieldTrip buffer for realtime data streaming?](/faq/how_fast_is_the_fieldtrip_buffer_for_realtime_data_streaming)
*  [Does the FieldTrip realtime buffer only work with MATLAB?](/faq/does_the_fieldtrip_realtime_buffer_only_work_with_matlab)
*  [How should I get started with the FieldTrip realtime buffer?](/faq/how_should_i_get_started_with_the_fieldtrip_realtime_buffer)

## Questions that pertain to corrupt datafiles
*  [How can I fix a corrupt CTF meg4 data file?](/faq/how_can_i_fix_a_corrupt_ctf_meg4_data_file)
*  [How can I fix a corrupt CTF res4 header file?](/faq/how_can_i_fix_a_corrupt_ctf_res4_header_file)
*  [How can I read corrupted (unsaved)_CTF_data?](/faq/how_can_i_read_corrupted_(unsaved)_ctf_data)
*  [I am having problems reading the CTF .hc headcoordinates file](/faq/i_am_having_problems_reading_the_ctf_*.hc_headcoordinates_file)
*  [How can I deal with a discontinuous Neuralynx recording?](/faq/discontinuous_neuralynx)

##  Distributed computing
*  [What are the different approaches I can take for distributed computing?](/faq/what_are_the_different_approaches_i_can_take_for_distributed_computing)

### Distributed computing with the MATLAB distributed computing toolbox
*  [How to get started with the MATLAB distributed computing toolbox?](/faq/how_to_get_started_with_the_matlab_distributed_computing_toolbox)

###  Distributed computing with fieldtrip/qsub on a HPC cluster
*  [How to get started with distributed computing using qsub?](/faq/how_to_get_started_with_distributed_computing_using_qsub)
*  [How to compile MATLAB code into stand-alone executables?](/faq/how_to_compile_matlab_code_into_stand-alone_executables)

### Distributed computing with fieldtrip/engine on a multicore computer
*  [How to get started with distributed computing using engine?](/faq/how_to_get_started_with_distributed_computing_using_engine)

###  Distributed computing with fieldtrip/peer on a ad-hoc cluster
*  [How to get started with peer distributed computing on my own desktop computer?](/faq/how_to_get_started_with_peer_distributed_computing_on_my_own_desktop_computer)
*  [How can I use the command-line peerslave and optimize the MATLAB licenses?](/faq/how_can_i_use_the_command-line_peerslave_and_optimize_the_matlab_licenses)
*  [How can I combine FieldTrip with peer distributed computing?](/faq/how_can_i_combine_fieldtrip_with_peer_distributed_computing)
*  [How can I read and write files if I use other people's peers?](/faq/how_can_i_read_and_write_files_if_i_use_other_people's_peers)
*  [What happens if a job fails to execute properly?](/faq/what_happens_if_a_job_fails_to_execute_properly)
*  [Why does peercellfun resubmit jobs that take too long to get started?](/faq/why_does_peercellfun_resubmit_jobs_that_take_too_long_to_get_started)
*  [How can I debug a problematic distributed job?](/faq/how_can_i_debug_a_problematic_distributed_job)
*  [What happens with a job that has an error on the slave?](/faq/what_happens_with_a_job_that_has_an_error_on_the_slave)
*  [How can I prevent a job from executing twice?](/faq/how_can_i_prevent_a_job_from_executing_twice)
*  [How should I call peercellfun when a function requires many inputs (e.g. key-value  pairs)?](/faq/how_should_i_call_peercellfun_when_a_function_requires_many_inputs_e.g._key-value_pairs)
*  [How can I set up the peer distributed computing on a single multicore computer?](/faq/how_can_i_set_up_the_peer_distributed_computing_on_a_single_multicore_computer)
*  [How can I set up the peer distributed computing on a small number of computers?](/faq/how_can_i_set_up_the_peer_distributed_computing_on_a_small_number_of_computers)
*  [How can I set up the peer distributed computing on a large linux cluster?](/faq/how_can_i_set_up_the_peer_distributed_computing_on_a_large_linux_cluster)
*  [Does a firewall affect the communication between peers?](/faq/does_a_firewall_affect_the_communication_between_peers)
*  [Why are the peers using multicast to announce themselves?](/faq/why_are_the_peers_using_multicast_to_announce_themselves)___
*  [How can I stop the different threads created by peermaster and peerslave?](/faq/how_can_i_stop_the_different_threads_created_by_peermaster_and_peerslave)
*  [How does the peer smartshare algorithm work?](/faq/how_does_the_peer_smartshare_algorithm_work)
*  [How does the peer smartmem algorithm work?](/faq/how_does_the_peer_smartmem_algorithm_work)
*  [How do I avoid having to allocate N copies of my data if I want to execute N jobs?](/faq/how_do_i_avoid_having_to_allocate_n_copies_of_my_data_if_i_want_to_execute_n_jobs)

##  MATLAB questions
*  [Why are so many of the interesting functions in the private directories?](/faq/why_are_so_many_of_the_interesting_functions_in_the_private_directories)
*  [MATLAB does not see the functions in the "private" directory](/faq/matlab_does_not_see_the_functions_in_the_"private"_directory)
*  [MATLAB version 7.3 (2006b)_crashes_when_I_try_to_do_...](/faq/matlab_version_7.3_(2006b)_crashes_when_i_try_to_do_...)
*  [MATLAB complains about a missing or invalid MEX file, what should I do?](/faq/matlab_complains_about_a_missing_or_invalid_mex_file,_what_should_i_do)
*  [How can I compile the mex files and command-line programs?](/faq/compile)
*  [How can I compile the mex files on 64 bit Windows?](/faq/how_can_i_compile_the_mex_files_on_64_bit_windows)
*  [How can I compile the mex files on OS X?](/faq/how_can_i_compile_the_mex_files_on_os_x)
*  [How many lines of code does Fieldtrip consist of?](/faq/how_many_lines_of_code_does_fieldtrip_consist_of)
*  [Should I add FieldTrip with all subdirectories to my MATLAB path?](/faq/should_i_add_fieldtrip_with_all_subdirectories_to_my_matlab_path)
*  [Can I prevent "external" toolboxes from being added to my MATLAB path?](/faq/can_i_prevent_"external"_toolboxes_from_being_added_to_my_matlab_path)
*  [What is the relation between "events" (such_as_triggers)_and_"trials"?](/faq/what_is_the_relation_between_"events"_(such_as_triggers)_and_"trials")
*  [How to select the correct SPM toolbox?](/faq/how_to_select_the_correct_spm_toolbox)
*  [How can I determine the number of threads that MATLAB uses?](/faq/how_can_i_determine_the_number_of_threads_that_matlab_uses)
*  [Can I use Octave instead of MATLAB?](/faq/can_i_use_octave_instead_of_matlab)
*  [What are the MATLAB requirements for using FieldTrip?](/faq/requirements)
*  [Which external toolboxes are used by FieldTrip?](/faq/external)
*  [Can I use FieldTrip without MATLAB license?](/faq/compiled)

## Code and development questions
*  [How are the various data structures defined?](/faq/how_are_the_various_data_structures_defined)
*  [What does a typical call to a FieldTrip function look like?](/faq/what_does_a_typical_call_to_a_fieldtrip_function_look_like)
*  [How can I debug my analysis script if a FieldTrip function gives an error?](/faq/how_can_i_debug_my_analysis_script_if_a_fieldtrip_function_gives_an_error)
*  [How can I keep track of the changes to the code?](/faq/how_can_i_keep_track_of_the_changes_to_the_code)
*  [Why is FieldTrip maintained in SVN and not in git?](/faq/why_is_fieldtrip_maintained_in_svn_and_not_in_git)

##  Organizational questions
*  [How to ask good questions to the community?](/faq/how_to_ask_good_questions_to_the_community)
*  [Why am I not allowed to post to the discussion list?](/faq/why_am_i_not_allowed_to_post_to_the_discussion_list)
*  [Why am I not receiving emails from the discussion list?](/faq/why_am_i_not_receiving_emails_from_the_discussion_list)
*  [Why am I receiving warnings about too many bouncing emails?](/faq/why_am_i_receiving_warnings_about_too_many_bouncing_emails)
*  [Why is my message rejected from the email discussion list?](/faq/why_is_my_message_rejected_from_the_email_discussion_list)
*  [How many people are subscribed to the email discussion list?](/faq/how_many_people_are_subscribed_to_the_email_discussion_list)
*  [How should I send example data to the developers?](/faq/how_should_i_send_example_data_to_the_developers)
*  [How should I refer to FieldTrip in my publication?](/faq/how_should_i_refer_to_fieldtrip_in_my_publication)
*  [Which version of FieldTrip should I download from the ftp server?](/faq/which_version_of_fieldtrip_should_i_download_from_the_ftp_server)
*  [I am having problems downloading from the ftp server](/faq/i_am_having_problems_downloading_from_the_ftp_server)
*  [I am working at the Donders, should I also download FieldTrip?](/faq/i_am_working_at_the_donders,_should_i_also_download_fieldtrip)
*  [Why is FieldTrip developed separately from EEGLAB?](/faq/why_is_fieldtrip_developed_separately_from_eeglab)
*  [Can I get an offline version of the wiki documentation?](/faq/can_i_get_an_offline_version_of_the_wiki_documentation)
*  [Can I use the FieldTrip logo on my poster?](/faq/can_i_use_the_fieldtrip_logo_on_my_poster)

##  Various other questions
*  [What usage information is FieldTrip tracking?](/faq/tracking)
*  [Why does my ICA output contain complex numbers?](/faq/why_does_my_ica_output_contain_complex_numbers)
*  [I used ICA on my MEG data from before 2012 and now FieldTrip crashes, why is that?](/faq/i_used_ica_on_my_meg_data_from_before_2012_and_now_fieldtrip_crashes,_why_is_that)
*  [How do I prevent FieldTrip from printing the time and memory after each function call?](/faq/how_do_i_prevent_fieldtrip_from_printing_the_time_and_memory_after_each_function_call)
*  [What types of datasets (and their respective analyses) are used on FieldTrip?](/faq/what_types_of_datasets_and_their_respective_analyses_are_used_on_fieldtrip)
*  [Where can I find open access MEG/EEG data?](/faq/open_data)
*  [Are the FieldTrip lectures available on video?](/faq/video)
*  [How should I prepare for the upcoming FieldTrip workshop?](/faq/how_should_i_prepare_for_the_upcoming_fieldtrip_workshop)
*  [How can I share my MEG or EEG dataset?](/faq/data_sharing)
*  [What are the units of the data and of the derived results?](/faq/units)
*  [Can I map different Electrode position layouts?](/faq/capmapping)
*  [How can I convert an anatomical MRI from DICOM into CTF format?](/faq/how_can_i_convert_an_anatomical_mri_from_dicom_into_ctf_format)
*  [How can I anonymize data processed in FieldTrip?](/faq/how_can_i_anonymize_fieldtrip_data)
*  [How can I anonymize a CTF dataset?](/faq/how_can_i_anonymize_a_ctf_dataset)
*  [How can I anonymize or deidentify an anatomical MRI?](/faq/how_can_i_anonymize_an_anatomical_mri)
*  [How can I anonymize DICOM files?](/faq/how_can_i_anonymize_dicom_files)