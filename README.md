# Hi, I'm Tim Lin

**M.Eng. in Autonomy & Robotics @ UIUC** (expected Dec 2027)

I'm a graduate student working at the intersection of robotics, perception, and machine learning. Previously M.S. in Opto-Mechatronics Engineering and B.S. in Mechanical Engineering at National Central University, Taiwan.

- **Interests:** robotics software, perception / computer vision, controls, autonomous systems
- **Currently:** Computer Vision (CS543), Principles of Safe Autonomy (ECE484) @ UIUC
- **Tech:** Python · C++ · Lua · TensorFlow/Keras · OpenCV · Arduino

## Featured work

### Label-free battery SOH estimation across temperatures
M.S. thesis (NCU, 2026). A CNN-LSTM model trained on 25 °C battery-pack data is transferred to 5 °C / 45 °C packs and to the public NASA PCoE cells with AdaBN: only the BatchNorm statistics are re-estimated on unlabeled target data, with no target labels and no backprop. 25 °C 12-fold cross-validation: 0.71% RMSE; on NASA cell B0006, RMSE drops from 11.68% (direct transfer) to 5.01%.
`Python` `TensorFlow/Keras` `scikit-learn`

### [島輝 DaoHui — smart Zhuyin input method](https://github.com/TimLin-1231/rime-asus-zhuyin)
A Traditional Chinese (Zhuyin) input method on the Rime engine, modeled on ASUS Smart Input (not affiliated with ASUS) and extended: inline preview, mid-sentence editing, typo correction, mixed Chinese/English typing, self-learning, and an on-device writing assistant (Harper + llama.cpp). Changes are measured with a Python harness that drives `rime.dll` against held-out test sets.
`Lua` `Python` `C++` `Swift`

| Platform | Repo | Download |
| --- | --- | --- |
| Windows 8.1–11 | [daohui-weasel](https://github.com/TimLin-1231/daohui-weasel) (fork of Weasel 小狼毫) | [latest release](https://github.com/TimLin-1231/daohui-weasel/releases/latest) |
| macOS 13+ | [daohui-squirrel](https://github.com/TimLin-1231/daohui-squirrel) (fork of Squirrel 鼠鬚管) | [pre-release builds](https://github.com/TimLin-1231/daohui-squirrel/releases) |

Contact: linting1231@gmail.com · [LinkedIn](https://www.linkedin.com/in/yu-ting-lin-641507286)
