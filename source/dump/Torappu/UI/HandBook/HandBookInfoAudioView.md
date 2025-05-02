# HandBookInfoAudioView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `UIPageFinder m_pageFinder`

- `Text _infoTextField`

- `GameObject _play`

- `GameObject _pause`

- `Transform _slider`

- `GameObject _showText`

- `CharWordData m_sourceData`

- `VoiceLangType m_voiceLangType`

- `String m_infoText`

- `String m_infoTitle`

- `HandBookInfoView m_parentView`

- `Int32 m_id`

- `Boolean m_onPlay`

- `Single m_allTime`

- `Single m_cacheTime`


## Methods

- `Void PlayAudio()`

- `Void ShowText()`

- `Void OnStopClick()`

- `Void StopAudioUI()`

- `Void PlayAudioClick()`

- `Void Initalize(Int32, InfoTextAudio, HandBookInfoView)`

- `Void UpdateVoiceStatus()`

- `Void OnDisable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoAudioView : MonoBehaviour, IHotfixable
{
	private UIPageFinder m_pageFinder; // 0x18
	private Text _infoTextField; // 0x28
	private GameObject _play; // 0x30
	private GameObject _pause; // 0x38
	private Transform _slider; // 0x40
	private GameObject _showText; // 0x48
	private CharWordData m_sourceData; // 0x50
	private VoiceLangType m_voiceLangType; // 0x58
	private String m_infoText; // 0x60
	private String m_infoTitle; // 0x68
	private HandBookInfoView m_parentView; // 0x70
	private Int32 m_id; // 0x78
	private Boolean m_onPlay; // 0x7c
	private Single m_allTime; // 0x80
	private Single m_cacheTime; // 0x84
	private static DelegateBridge __Hotfix0_PlayAudio; // 0x0
	private static DelegateBridge __Hotfix0_ShowText; // 0x8
	private static DelegateBridge __Hotfix0_OnStopClick; // 0x10
	private static DelegateBridge __Hotfix0_StopAudioUI; // 0x18
	private static DelegateBridge __Hotfix0_PlayAudioClick; // 0x20
	private static DelegateBridge __Hotfix0_Initalize; // 0x28
	private static DelegateBridge __Hotfix0_UpdateVoiceStatus; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2eac464 VA: 0x75954c4464
	public Void PlayAudio() { }
	// RVA: 0x2eac6b8 VA: 0x75954c46b8
	public Void ShowText() { }
	// RVA: 0x2eac738 VA: 0x75954c4738
	public Void OnStopClick() { }
	// RVA: 0x2eac7d4 VA: 0x75954c47d4
	public Void StopAudioUI() { }
	// RVA: 0x2eac89c VA: 0x75954c489c
	public Void PlayAudioClick() { }
	// RVA: 0x2eac9f4 VA: 0x75954c49f4
	public Void Initalize(Int32 id, InfoTextAudio viewModel, HandBookInfoView parentView) { }
	// RVA: 0x2eacb4c VA: 0x75954c4b4c
	public Void UpdateVoiceStatus() { }
	// RVA: 0x2eacc70 VA: 0x75954c4c70
	private Void OnDisable() { }
	// RVA: 0x2eaccec VA: 0x75954c4cec
	private Void Update() { }
	// RVA: 0x2eacde8 VA: 0x75954c4de8
	public Void .ctor() { }
}
```