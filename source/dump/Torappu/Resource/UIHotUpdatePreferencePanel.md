# UIHotUpdatePreferencePanel

**Namespace:** `Torappu.Resource`


## Fields

- `UIFadeFloatPanel _fadeFloatPanel`

- `TwoStateToggle _fullToggle`

- `Text _fullUnselectLabel`

- `Text _fullSelectLabel`

- `TwoStateToggle _baseToggle`

- `Text _baseUnselectLabel`

- `Text _baseSelectLabel`

- `Options m_options`


## Methods

- `Void Show(Options)`

- `Void OnFullToggleClick()`

- `Void OnBaseToggleClick()`

- `Void OnQuitBtnClick()`

- `Void OnConfirmBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class UIHotUpdatePreferencePanel : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _fadeFloatPanel; // 0x18
	private TwoStateToggle _fullToggle; // 0x20
	private Text _fullUnselectLabel; // 0x28
	private Text _fullSelectLabel; // 0x30
	private TwoStateToggle _baseToggle; // 0x38
	private Text _baseUnselectLabel; // 0x40
	private Text _baseSelectLabel; // 0x48
	private Options m_options; // 0x50
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_OnFullToggleClick; // 0x8
	private static DelegateBridge __Hotfix0_OnBaseToggleClick; // 0x10
	private static DelegateBridge __Hotfix0_OnQuitBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3744cd0 VA: 0x7595d5ccd0
	public Void Show(Options options) { }
	// RVA: 0x3744f10 VA: 0x7595d5cf10
	public Void OnFullToggleClick() { }
	// RVA: 0x3744f9c VA: 0x7595d5cf9c
	public Void OnBaseToggleClick() { }
	// RVA: 0x3745028 VA: 0x7595d5d028
	public Void OnQuitBtnClick() { }
	// RVA: 0x37450ac VA: 0x7595d5d0ac
	public Void OnConfirmBtnClick() { }
	// RVA: 0x37451c8 VA: 0x7595d5d1c8
	public Void .ctor() { }
}
```