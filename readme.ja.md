# DeviceConnect WebAPI �ɂ���

Device Connect WebAPI�̓X�}�[�g�t�H����ŉ��z�T�[�o�Ƃ��ē��삷��WebAPI�ŁA�l�X�ȃE�F�A���u���f�o�C�X��IoT�f�o�C�X��Web�u���E�U��A�v�����瓝��I�ȋL�q�ŊȒP�ɗ��p���邱�Ƃ��ł��܂��B

* ������Ƃ��āAAndroid�AiOS�ɑΉ����Ă��܂��BWeb�u���E�U�Ƃ��Ă�Chrome�ASafari�AFirefox�œ�����m�F���Ă��܂��B
  _�����ꂼ��̓�����ŗ��p�ł���Ή��f�o�C�X�͈قȂ�܂��B_
* ���z�T�[�o�ɂ��REST/WebSocket��WebAPI�ɂ��A�C�ӂ̊J�����������p���������܂��B
* �R���e���c�J����e�Ղɂ��邽�߂ɁAJavascript�pSDK�AAndroid�pSDK�AiOS�pSDK��p�ӂ��Ă��܂��B
* �@�\�g���̂��߂̃v���O�C���J���pSDK��p�ӂ��Ă���܂��B�C�ӂ�WebAPI�@�\�̒ǉ����\�ł��B
* �������[�J���l�b�g���[�N��ɂ���DeviceConnect WebAPI���Z�b�g�A�b�v���ꂽAndroid�[�����ݒ�ύX�ŗ��p�ł��܂��i�Z�L�����e�B��̃��X�N�ɂ��Ă����ӂ��������K�v������܂��j�B



# �T���v���ł̓���m�F�iAndroid�p�j
* /DeviceConnect/Bin/demoWebSite.zip
## Android�[���ł�Chrome�u���E�U����̓���m�F

�P�DAndroid�̓����X�g���[�W�Ƀf���R���e���c���t�H���_���쐬���i[��]"dConnect"�j�A
�@�@�����ɃT���v����demoWebSite�t�H���_�ȉ��̂��ׂẴt�@�C�����R�s�[���Ă��������B
```
Android root
   ������ mnt
       ������ sdcard
           ������ dConnect #�����Ƀt�H���_���쐬
                ������ demoWebSite #������javaScript�̃T���v�����R�s�[
```

�Q�DChrome�u���E�U�̃A�h���X���ɓ����X�g���[�W��URI���L�����A
�@�@�����X�g���[�W�ɂ���Web�R���e���c�ɃA�N�Z�X���Ă��������B
```
�@�@�@[��]�@file:///storage/emulated/0/dConnect/demoWebSite/index.html
```

�R�D"Download APK"�̃����N����ADevice Connect�{�̂�"DeviceConnectManager"�A
�@�@�f�o�C�X�v���O�C����"Android Host"���_�E�����[�h���A�C���X�g�[�����Ă��������B
�@�@_���ݒ�̃Z�L�����e�B����A�񋟌��s���̃A�v���̃C���X�g�[���̋����K�v�ł��B_

�S�D�g�b�v�y�[�W�ɖ߂��Ă��������B

�T�D"Launch UI-App"�̃����N����DeviceConnectWebAPI�̓�������m�F���������B
  �ECheck�{�^����DeviceConnectWebAPI�̓���󋵂̊m�F���s���܂��B
  �E���N���̏ꍇ�A"Device Connect was not foud."�ƕ\������܂��B
  �EDeviceConnectManager���C���X�g�[������Ă���΁A�ݒ��ʂ��\������܂��B
  �EDeviceConnectManager��ON�ɂ���Web��ʂɖ߂�A������xCheck�{�^����������
  �EDevice Connect API version:1.0�ƕ\������܂��B
  �EaccessToken�{�^���ŃR���e���c����̃f�o�C�X�@�\�A�N�Z�X�������܂��B
  �ESearch Device�{�^���������ƃC���X�g�[������Ă���v���O�C���̃��X�g���\������܂��B
  �EHOST��I�ԂƗ��p�ł���@�\�̈ꗗ�iProfile List�j���\������܂��B
  �E��������Avibration��I�сAVibrate��I�Ԃƒ[�����U�����܂��i�ŏ��̗��p���Ƀv���O�C�����p�̋����K�v�ł��j�B



##�O������̃A�N�Z�X�ɂ���

* demoWebSite��HTML��IP�A�h���X�̃p�����[�^��t�����邱�ƂŁA���[�J���l�b�g���[�N��̑��̒[���œ��삷��DeviceConnect WebAPI�̑�����\�ɂȂ�܂��B�������A���삳��鑤�̒[���Ɉȉ��̐ݒ肪�K�v�ł��B
 _�����u�ňӐ}���Ȃ��[���̑��삨��уf�[�^�Q�Ƃ�����郊�X�N�������܂��B�M�����o���Ȃ����[�J���l�b�g���[�N���ł͗��p���Ȃ��ł��������B_

�P�D��L�̓���m�F�Ɠ��l�̎菇�ŁA����Ώۂ̒[����DeviceConnect WebAPI���Z�b�g�A�b�v���Ă��������B

�Q�DDeviceConnectManager��Android�̃����`���[����N�����ADeviceConnectManager����UOFF�ɂ��Ă��������B

�R�DAllow External IP�̃`�F�b�N��L�������ADeviceConnectManager��ON�ɂ��Ă��������B

�S�D���삷�鑤�iPC���j��demoWebSite����HTML���J���A����Ώۂ�IP�A�h���X�̃p�����[�^��t�����Ă��������B
```
�@�@�@[��]�@file:///C:/demoWebSite/demo/index.html?ip=192.168.13.3
```
   _�����u�ňӐ}���Ȃ��[���̑��삨��уf�[�^�Q�Ƃ�����郊�X�N�������܂��B�M�����o���Ȃ����[�J���l�b�g���[�N���ɐڑ������\��������ꍇ��DeviceConnectManager��Allow External IP�̃`�F�b�N�𖳌������Ă�������_



# �Ή��f�o�C�X
<table>
  <tr>
    <td>���[�J�[</td>
    <td>���i��</td>
    <td>�@����</td>
    <td>�Ή��v���O�C��</td>
    <td>���l</td>
  </tr>
  <tr>
    <td>SONY</td>
    <td>SmartWatchMN2</td>
    <td>�r���v�^�f�o�C�X</td>
    <td>�l�m�Q�^�r�v�Q �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>SONY</td>
    <td>SmartWatchSW2</td>
    <td>�r���v�^�f�o�C�X</td>
    <td>�l�m�Q�^�r�v�Q �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Orbotix</td>
    <td>Sphero 2.0</td>
    <td>�{�[���^�X�}�[�g�g�C</td>
    <td>�r���������� �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Game Technologies</td>
    <td>DICE+</td>
    <td>�T�C�R���^�X�}�[�g�g�C</td>
    <td>�c�h�b�d�{ �v���O�C��</td>
    <td>�J���Ҍ����t�@�[���E�F�A�ւ̃A�b�v�f�[�g���K�v�ł��B</td>
  </tr>
  <tr>
    <td>Philips</td>
    <td>hue</td>
    <td>�X�}�[�g���C�g</td>
    <td>������ �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Philips</td>
    <td>Bloom Lamp</td>
    <td>�X�}�[�g���C�g</td>
    <td>������ �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Philips</td>
    <td>LightStrips</td>
    <td>�X�}�[�g���C�g</td>
    <td>������ �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>IRKit</td>
    <td>IRKit</td>
    <td>�ԊO�������R��</td>
    <td>�h�������� �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Epson</td>
    <td>Moverio BT-200</td>
    <td>���K�l�^�f�o�C�X</td>
    <td>�`�������������g������ �v���O�C��</td>
    <td>�ʂ̊g���@�\�ɂ��Ή��\��</td>
  </tr>
  <tr>
    <td>Vuzix</td>
    <td>M100 Smart Glass</td>
    <td>���K�l�^�f�o�C�X</td>
    <td>�`�������������g������ �v���O�C��</td>
    <td>�ʂ̊g���@�\�ɂ��Ή��\��</td>
  </tr>
  <tr>
    <td>�E�G�X�g���j�e�B�X</td>
    <td>Inforod</td>
    <td>���K�l�^�f�o�C�X</td>
    <td>�`�������������g������ �v���O�C��</td>
    <td>�ʂ̊g���@�\�ɂ��Ή��\��</td>
  </tr>
  <tr>
    <td>SONY</td>
    <td>DSC-QX100</td>
    <td>�����Y�X�^�C���J����</td>
    <td>�r�������b���������� �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>SONY</td>
    <td>DSC-QX10</td>
    <td>�����Y�X�^�C���J����</td>
    <td>�r�������b���������� �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Pebble</td>
    <td>Pebble</td>
    <td>�r���v�^�f�o�C�X</td>
    <td>�o�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>-</td>
    <td>Android�[�� Ver4.0�ȍ~</td>
    <td>Android�[��</td>
    <td>�`�������������g������ �v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>LG</td>
    <td>G Watch</td>
    <td>Android  Wear�[��</td>
    <td>�v�������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Samsung</td>
    <td>Gear Live</td>
    <td>Android  Wear�[��</td>
    <td>�v�������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Google</td>
    <td>ChromeCast</td>
    <td>HDMI�h���O��</td>
    <td>�b�����������b������ �v���O�C��</td>
    <td>Google Cast SDK Developer Console�̃y�[�W�ŁA�f�o�C�X��Receiver�A�v���̓o�^���K�v�ɂȂ�܂��B</td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>UA-767PBT-C</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>UA-851PBT-C</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>TM-2656VPM</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>UC-321PBT-C</td>
    <td>�̏d�v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HEM-708-IT</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HBF-206IT</td>
    <td>�̏d�̑g���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HHX-IT1</td>
    <td>�����ʌv</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>UA-772</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�G�[�E�A���h�E�f�B�[</td>
    <td>UW201</td>
    <td>�����ʌv</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HEM-7250IT</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HBF-208IT</td>
    <td>�̏d�̑g���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>�I�������w���X�P�A</td>
    <td>HBF-215IT</td>
    <td>�̏d�̑g���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>ESTERA</td>
    <td>FS-500</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>ESTERA</td>
    <td>FS-700</td>
    <td>�����ʌv</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>YAMASA</td>
    <td>EX-950</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>MSFV01</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>MT-KT02DZ</td>
    <td>���s���x�v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>C215</td>
    <td>�̉��v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>ES-H700D</td>
    <td>�����v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>ZS-NS05</td>
    <td>�p���X�I�L�V���[�^</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>TERUMO</td>
    <td>WT-B100DZ</td>
    <td>�̑g���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Polar</td>
    <td>H7</td>
    <td>�S���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>
  <tr>
    <td>Mio Global</td>
    <td>Mio Alpha</td>
    <td>�S���v</td>
    <td>���g�����������v���O�C��</td>
    <td></td>
  </tr>

</table>

* �e���[�J�[�������ۏႷ����̂ł͂���܂���
* ���p�ł���@�\�͊e�@��ňقȂ�܂�
* ���p����J���p���C�u�����̓s���ɂ��A�v���O�C���̃\�[�X�R�[�h�͈ꕔ�@��ɂ��Ă̊J���ƂȂ�܂�
* �e��h�L�������g�̐����A�Ή��f�o�C�X�̊g��ɂ��Ă������i�߂Ă����\��ł��B
* ���֐��̉��P��Z�L�����e�B����̂��߁A�d�l���ύX�ƂȂ�ꍇ������܂��B�\�߂��������������B









