# Step 032B Hygiene Tool Status

Step 032B adds a click-to-clean Windows entrypoint.

```text
entrypoint=RUN_PROJECT_HYGIENE.bat
classify_patch_notes=true
classify_audit_reports=true
remove_known_stale_files=true
remove_pycache_and_pyc=true
remove_runtime_pid_state=true
delete_registry=false
delete_fixtures=false
delete_data_outputs=false
delete_build_logs=false
delete_verify_scripts=false
delete_source_modules=false
delete_node_modules_or_venv=false
```

Run the bat from the project root, then run:

```text
python tools/verify_step_032b_hygiene.py
```

Next normal build step remains Step 033.
