# SettingVoiceLangItem

**Namespace:** `Torappu.UI.Setting`


## Fields

- `Text _textBtn`

- `VoiceLangType m_voiceLang`


## Methods

- `Void Setup(VoiceLangType, Action`1)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingVoiceLangItem : MonoBehaviour, IHotfixable
{
	private Text _textBtn; // 0x18
	private Action`1 m_onClicked; // 0x20
	private VoiceLangType m_voiceLang; // 0x28
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2478f18 VA: 0x7594a90f18
	public Void Setup(VoiceLangType voiceLang, Action`1 onClicked) { }
	// RVA: 0x247bbec VA: 0x7594a93bec
	public Void EventOnClicked() { }
	// RVA: 0x247bc74 VA: 0x7594a93c74
	public Void .ctor() { }
}
```