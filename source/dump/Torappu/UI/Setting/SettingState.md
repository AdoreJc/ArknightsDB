# SettingState

**Namespace:** `Torappu.UI.Setting`


## Fields

- `SettingPanel _settingPanel`

- `Transform _panelAccount`

- `Transform _panelOthers`

- `GameObject _panelDynIllustSetting`

- `GameObject _panelDynIllustRes`

- `GameObject _tabsDynIllustLoadStrategy`

- `GameObject _panelDynIllustStart`

- `GameObject _tabsDynEntrance`

- `GameObject _tabsDynEntranceLoginStrategy`

- `GameObject _textDynIllustCommonTip`

- `GameObject _textDynIllustDownloadTip`

- `GameObject _textDynEntranceCommonTip`

- `GameObject _textDynEntranceDownloadTip`

- `GameObject _textDynEntranceLoginCommonTip`

- `GameObject _textDynEntranceLoginDownloadTip`

- `TwoStateToggle _videoDownloadToggle`

- `TwoStateToggle _voiceDownloadToggle`

- `TwoStateToggle _dynIllustDownloadToggle`

- `SimpleLayoutContent _voiceLangBatchContainer`

- `VoiceLangAdapter m_voiceLangAdapter`

- `Boolean m_isInited`


## Methods

- `Void EventOnBtnBackClick()`

- `Void EventOnBtnResetClick()`

- `Void EventOnBtnVideoDownloadClick()`

- `Void EventOnBtnVoiceDownloadClick()`

- `Void EventOnBtnDynIllustDownloadClick()`

- `Void EventOnBtnVoiceLangCustomizeClick()`

- `Void PlayerQuit()`

- `Void _OnVoiceLangBatchSetClicked(VoiceLangType)`

- `Void _OnSettingCategoryClicked(SettingCategory)`

- `Void _InitIfNot()`

- `Void _BatchVoiceLangRequest(VoiceLangType)`

- `Void _SetDynIllustPartStatus()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingState : PopupFloatState
{
	private SettingPanel _settingPanel; // 0x70
	private Transform _panelAccount; // 0x78
	private Transform _panelOthers; // 0x80
	private GameObject _panelDynIllustSetting; // 0x88
	private GameObject _panelDynIllustRes; // 0x90
	private GameObject _tabsDynIllustLoadStrategy; // 0x98
	private GameObject _panelDynIllustStart; // 0xa0
	private GameObject _tabsDynEntrance; // 0xa8
	private GameObject _tabsDynEntranceLoginStrategy; // 0xb0
	private GameObject _textDynIllustCommonTip; // 0xb8
	private GameObject _textDynIllustDownloadTip; // 0xc0
	private GameObject _textDynEntranceCommonTip; // 0xc8
	private GameObject _textDynEntranceDownloadTip; // 0xd0
	private GameObject _textDynEntranceLoginCommonTip; // 0xd8
	private GameObject _textDynEntranceLoginDownloadTip; // 0xe0
	private TwoStateToggle _videoDownloadToggle; // 0xe8
	private TwoStateToggle _voiceDownloadToggle; // 0xf0
	private TwoStateToggle _dynIllustDownloadToggle; // 0xf8
	private SimpleLayoutContent _voiceLangBatchContainer; // 0x100
	private VoiceLangAdapter m_voiceLangAdapter; // 0x108
	private Boolean m_isInited; // 0x110
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBtnBackClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnResetClick; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnVideoDownloadClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBtnVoiceDownloadClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnDynIllustDownloadClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnVoiceLangCustomizeClick; // 0x38
	private static DelegateBridge __Hotfix0_PlayerQuit; // 0x40
	private static DelegateBridge __Hotfix0__OnVoiceLangBatchSetClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnSettingCategoryClicked; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__BatchVoiceLangRequest; // 0x60
	private static DelegateBridge __Hotfix0__SetDynIllustPartStatus; // 0x68
	private static DelegateBridge __Hotfix0__CheckIfVoicePrefEnabled; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2476a38 VA: 0x7594a8ea38
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2476a9c VA: 0x7594a8ea9c
	protected override Void OnEnter() { }
	// RVA: 0x2476f48 VA: 0x7594a8ef48
	public Void EventOnBtnBackClick() { }
	// RVA: 0x2476fbc VA: 0x7594a8efbc
	public Void EventOnBtnResetClick() { }
	// RVA: 0x24771b4 VA: 0x7594a8f1b4
	public Void EventOnBtnVideoDownloadClick() { }
	// RVA: 0x24773ac VA: 0x7594a8f3ac
	public Void EventOnBtnVoiceDownloadClick() { }
	// RVA: 0x2477624 VA: 0x7594a8f624
	public Void EventOnBtnDynIllustDownloadClick() { }
	// RVA: 0x247781c VA: 0x7594a8f81c
	public Void EventOnBtnVoiceLangCustomizeClick() { }
	// RVA: 0x2477910 VA: 0x7594a8f910
	public Void PlayerQuit() { }
	// RVA: 0x2477b08 VA: 0x7594a8fb08
	private Void _OnVoiceLangBatchSetClicked(VoiceLangType voiceLang) { }
	// RVA: 0x2477e34 VA: 0x7594a8fe34
	private Void _OnSettingCategoryClicked(SettingCategory category) { }
	// RVA: 0x2476b10 VA: 0x7594a8eb10
	private Void _InitIfNot() { }
	// RVA: 0x2478774 VA: 0x7594a90774
	private Void _BatchVoiceLangRequest(VoiceLangType langType) { }
	// RVA: 0x24783f0 VA: 0x7594a903f0
	private Void _SetDynIllustPartStatus() { }
	// RVA: 0x2477d54 VA: 0x7594a8fd54
	private static Boolean _CheckIfVoicePrefEnabled(VoiceLangType voiceLangType) { }
	// RVA: 0x24789b4 VA: 0x7594a909b4
	public Void .ctor() { }
	// RVA: 0x2478a24 VA: 0x7594a90a24
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```