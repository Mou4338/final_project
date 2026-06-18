# Submission Checklist

Use this folder as the contents of your GitHub repository.

## GitHub URLs to Submit

- README.md: `https://github.com/Mou4338/final_project/blob/main/README.md`
- EmotionDetection/__init__.py: `https://github.com/Mou4338/final_project/blob/main/EmotionDetection/__init__.py`

If your repository uses a different branch name, replace `main` in the URLs with that branch name.

## Screenshots Requested By The Course

- `1_folder_structure.png`
- `2a_emotion_detection.png`
- `2b_application_creation.png`
- `3a_output_formatting.png`
- `3b_formatted_output_test.png`
- `4a_packaging.png`
- `4b_packaging_test.png`
- `5a_unit_testing.png`
- `5b_unit_testing_result.png`
- `6a_server.png`
- `6b_deployment_test.png`
- `7a_error_handling_function.png`
- `7b_error_handling_server.png`
- `7c_error_handling_interface.png`
- `8a_server_modified.png`
- `8b_static_code_analysis.png`

## Commands To Capture In Screenshots

```bash
python -c "from EmotionDetection.emotion_detection import emotion_detector; print(emotion_detector('I love this new technology.'))"
python -c "import EmotionDetection; print(EmotionDetection.emotion_detector('I love this new technology.'))"
python -m unittest test_emotion_detection.py
python server.py
pylint server.py
```
