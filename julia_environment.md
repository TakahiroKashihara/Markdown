# **python,julia��Notebook�ŏ������߂̊��\�z(Windows)**<!-- omit in toc -->
- [**1. ���X�̃\�t�g���C���X�g�[��**](#1-���X�̃\�t�g���C���X�g�[��)
- [**2. �C���X�g�[�������\�t�g�̐ݒ�**](#2-�C���X�g�[�������\�t�g�̐ݒ�)
  - [**2.1. julia(WSL���œ������ꍇ�̏���)**](#21-juliawsl���œ������ꍇ�̏���)
  - [**2.2. julia**](#22-julia)
  - [**2.3. VScode**](#23-vscode)

�ȉ��ł́Apython��julia��Jupyter Notebook�ŏ����A���s���邽�߂̎菇���������B

�ŏ��ɁAAnaconda����Jupyter Notebook�ō�Ƃ���ꍇ��������A���̎���VScode�ō�Ƃ���ꍇ���������B

�M�҂̒m���s���̂��߁A�s�v���邢�͏d�������ߒ����܂܂�Ă��邩������Ȃ����Ƃ�\�ߒf���Ă����B�܂��AVScode�̊��\�z�����K�v�̖������ɂƂ��ẮAAnaconda���C���X�g�[������K�v�͖����B
�������AAnaconda���C���X�g�[�����Ă��Ȃ����Ƃɂ���āA�ȉ��̉ߒ��̒��ł��܂����삵�Ȃ����̂����邩������Ȃ��B���̏ꍇ�ɂ��Ă͍J��Web�y�[�W�Ȃǂ��Q�l�ɂ��Ă������������B
# **1. ���X�̃\�t�g���C���X�g�[��**

���񈵂��\�t�g�͈ȉ���URL����C���X�g�[���ł���BWSL����julia���g���ꍇ�́ALinux�p���C���X�g�[������K�v������B�܂��Acommandprompt��WindowsPoewrshell���Ŏg���ꍇ�́Ajulia�̃C���X�g�[������PATH��ʂ��Ă����ƕ֗��B

| �\�t�g�� | URL |
| ---- | ---- |
| julia | https://julialang.org/downloads/  
| Anaconda | https://www.anaconda.com/products/individual |
| VScode | https://code.visualstudio.com/download |

# **2. �C���X�g�[�������\�t�g�̐ݒ�**
## **2.1. julia(WSL���œ������ꍇ�̏���)**
WSL�œ������ꍇ�́A�_�E�����[�h�����t�@�C�����ړ�����Ƃ悢�炵���B
����ɂ��ẮA�ȉ���Web�y�[�W���Q�l�ɂȂ�;

http://kimamani-programing.info/2019/12/07/wsl%E3%81%ABjulia%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%97%E3%81%A6%E3%81%BF%E3%81%9F%EF%BC%81%EF%BC%81/

���Ȃ݂ɁA�M�҂̊��ł́A���̃y�[�W���́utar ..�v�R�}���h���usudo�v�����Ȃ��Ǝ��s�ł��Ȃ������B

## **2.2. julia**
julia��PATH���ʂ��Ă����(WSL�̏ꍇ�́A��̎葱���ɂ���ăV���{���b�N�����N���쐬�ł��Ă����)�A�R�}���h���C���Łujulia�v�Ɠ��͂���ƈȉ��̉�ʂɂȂ�͂��ł���B![](julia�N�����.png)

�N�������̂�REPL�ƌĂ΂��Θb�^���s���ŁA���̉�ʂ�julia�̃R�[�h����͂���Ǝ��s���Ă����B

�����Ɂuprintln("Hello")�v�Ɠ��͂��Ă݂悤�B�@![](julia_println.png)

���ɁA" ] "�Ɠ��͂��Ă݂悤�B����ɂ��A���͑҂��̍s�̐F���ς��A�p�b�P�[�W���[�h�ƌĂ΂�郂�[�h�ɂȂ�B�p�b�P�[�W���[�h�ł́Ajulia�̐F��ȃp�b�P�[�W��ǉ��ł���B�Ⴆ�΁A�O���t�Ȃǂ��������߂́uPlots�v�Ƃ����p�b�P�[�W�̓f�t�H���g�ł͓����Ă��炸�A�p�b�P�[�W���[�h�Œǉ�����K�v������B

**����K�v�Ȃ̂́uIJulia�v�Ƃ����p�b�P�[�W�Ȃ̂ŁA�uadd IJulia�v�Ɠ��͂���B**

�p�b�P�[�W���[�h���猳�ɖ߂邽�߂ɂ́A�uCtrl + C�v�Ɠ��͂���B���̏�ԂŁA�uusing IJulia�v�Ɠ��͂�����Ɂunotebook()�v�Ɠ��͂���ƁAAnaconda��Jupyter Notebook���J�����͂��ł���B���̏�ԂŁA����julia��Anaconda��Notebook�ŏ������Ƃ��ł���B�������ANotebook�̓R�}���h���C������ł͂Ȃ�Anaconda����J�����Ƃ��ł���B�܂��AAnaconda��Jupyter Lab�ł�julia���������Ƃ��ł���悤�ɂȂ��Ă���B

**VScode��plot�Ȃǂ����邽�߂ɂ́A����Ƀp�b�P�[�W���[�h��build IJulia�Ɠ��͂���K�v������B**
## **2.3. VScode**
VScode��julia���������߂ɂ́A�ujulia�v�Ƃ����g���@�\���C���X�g�[������K�v������B

�܂��ANotebook���g�����߂ɂ́A�uJupyter�v�Ƃ����g���@�\���K�v�ł���B

VScode�ŁuCtrl + Shift + P�v�Ɠ��͂��A�uJupyter:Create New Jupyter Notebook�v�Ɠ��͂���ƁA.ipynb�t�@�C�����쐬�����B
![](ipynb.png)

**�������A���̎��_�ł͉E���Kernel�Ƃ���julia��I�Ԃ��Ƃ��ł��Ȃ��B�܂��A�����Python�����I�ׂȂ��B**

julia�̃R�[�h�������Ď��s����ɂ́A�ȉ��̂悤��**VScode�̐ݒ�ɏ������ޕK�v������**�B(settings.json)�Ⴆ�΁A�M�҂̏ꍇ�͎��̂悤�ɂȂ��Ă���G

{
    "terminal.integrated.commandsToSkipShell": [
        "language-julia.interrupt"
    ],
    "julia.symbolCacheDownload": true,
    "julia.executablePath": "C:\\Users\\taka\\AppData\\Local\\Programs\\Julia-1.7.1\\bin\\julia.exe",
    "security.workspace.trust.untrustedFiles": "open",
    "julia.enableTelemetry": true
}

�ȏ�ŁAVScode��Jupyter Notebook��julia���g�����Ƃ��ł���B




