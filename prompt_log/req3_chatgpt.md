# Requirement 3: Test cases for ONE physical product — Prompt Log / Session

## Session Metadata

- **Student Name**: Dang Truong Nguyen
- **Student ID**: 23127438
- **Date**: 2026-06-05
- **Model**: ChatGPT (GPT-4o / GPT-4-turbo)
- **Task**: Requirement 3: Design and execute 15 QA test cases for physical product (Leobog Hi75C Pro keyboard), record actual results and verdicts.

## Actions Log

| Step | Time | Action | Description |
| :--- | :--- | :--- | :--- |
| 1 | 2026-06-05 09:15 | Prompt: "hãy thiết kế 15 test case cho bàn phím leobog hi75c pro" | Requested ChatGPT to design 15 QA test cases for Leobog Hi75C Pro keyboard in Vietnamese. |
| 2 | 2026-06-05 09:16 | Response: Generated 15 QA test cases | ChatGPT produced 15 test cases covering basic functionality (wired, Bluetooth, 2.4GHz, knob, keys) with objectives, steps, expected results. |
| 3 | 2026-06-05 10:30 | Prompt: "Design 15 test cases (Objective / Input / Steps / Expected / Actual / Verdict)" | Requested restructuring into a formal test case table format with Input and Verdict columns included. |
| 4 | 2026-06-05 10:31 | Response: Generated detailed structured QA test cases | ChatGPT reformatted all 15 test cases into the requested column structure with edge cases and potential defect suggestions. |
| 5 | 2026-06-05 11:45 | Prompt: "làm ra cái bảng md đi" | Requested conversion to Markdown table format for embedding into report. |
| 6 | 2026-06-05 11:46 | Response: Generated markdown table | ChatGPT produced a complete Markdown table with all 15 test cases in proper table syntax. |
| 7 | 2026-06-05 13:20 | Prompt: "TBD là j d" | Asked for clarification of "TBD" abbreviation found in the test cases (To Be Determined). |
| 8 | 2026-06-05 13:21 | Response: Explained TBD = To Be Determined | ChatGPT explained TBD placeholder meaning and suggested replacing with actual results after physical testing. |
| 9 | 2026-06-05 14:30 | Prompt: "sửa test case này thành bấm nút xoay trên bàn phím khi nút đó đang ở chế độ chuyển màu" | Requested modification of knob test case to specifically test RGB color switching using the rotary knob. |
| 10 | 2026-06-05 14:31 | Response: Updated TC04 | ChatGPT revised TC04 to describe RGB control via knob rotation in RGB mode instead of generic knob test. |
| 11 | 2026-06-05 15:45 | Prompt: "ko có nút prtsrc thì có phải fail test ko" | Asked whether missing PrtSc key constitutes a test failure. |
| 12 | 2026-06-05 15:46 | Response: Explained missing PrtSc key handling | ChatGPT clarified that missing key is only a defect if the product manual/spec claims it exists; otherwise it's a design choice. |
| 13 | 2026-06-05 16:00 | Physical execution of test cases | Manually executed all 15 test cases on physical Leobog Hi75C Pro keyboard, recorded actual results and verdicts. |
| 14 | 2026-06-05 17:00 | Finalized test case table | Integrated actual results (Pass/Fail) into final table; 4 tests failed (TC06 duplicate key detection, TC07 N-key rollover, TC11 mode switching freeze, TC14 noise level, TC15 missing PrtSc key). |

## Test Cases Summary

| TC ID | Objective | Verdict |
| :--- | :--- | :--- |
| TC01 | Verify keyboard works in wired mode | Pass |
| TC02 | Verify Bluetooth pairing | Pass |
| TC03 | Verify 2.4GHz connection | Pass |
| TC04 | Verify knob RGB mode switching | Pass |
| TC05 | Verify volume knob function | Pass |
| TC06 | Verify all keys register correctly | Fail |
| TC07 | Verify N-key rollover | Fail |
| TC08 | Verify battery charging | Pass |
| TC09 | Verify auto sleep mode | Pass |
| TC10 | Verify wake-up from sleep mode | Pass |
| TC11 | Verify rapid switching between all connection modes | Fail |
| TC12 | Verify receiver removal during active typing | Pass |
| TC13 | Verify Bluetooth stability at very low battery | Pass |
| TC14 | Verify noise of keyboard | Fail |
| TC15 | Verify keyboard support PrtScr button | Fail |

- **Total Test Cases**: 15
- **Passed**: 10
- **Failed**: 5
- **Defects Found**:
  - TC06: Keyboard tester cannot differentiate duplicate keys (Shift, Alt, Ctrl)
  - TC07: Only 1 key detected at a time during N-key rollover test
  - TC11: Keyboard freezes when switching from 2.4GHz to wired mode
  - TC14: Typing noise 45–55dB causes discomfort
  - TC15: Missing PrtSc key
- **Target Submission File**: `23127438.md`
- **Test Case Export**: `sheet/test_case.csv`

## Tools Used

- ChatGPT (GPT-4o / GPT-4-turbo) – conversation for test case design and refinement
- Manual physical testing – execution of test cases on Leobog Hi75C Pro
- Keyboard tester (https://www.keyboardtester.com/tester.html) – key registration and rollover verification
- Decibel X App – noise measurement
- File editing (write tool) – exported test cases to CSV and Markdown
