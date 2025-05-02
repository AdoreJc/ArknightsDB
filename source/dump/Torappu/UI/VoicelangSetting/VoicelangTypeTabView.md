# VoicelangTypeTabView

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `Text m_typeText`

- `GameObject m_selectGo`

- `RectTransform m_rectTrans`

- `GameObject m_goCount`

- `GameObject m_goShu`

- `Text m_lbCount`

- `UISelectGroupTypeEvent m_listener`

- `VoicelangTypeViewModel m_model`


## Methods

- `Void UpdateView(VoicelangTypeViewModel)`

- `Void SetIsLastTab(Boolean)`

- `Void SetSelectEvent(UISelectGroupTypeEvent)`

- `Void SetWidth(Single)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangTypeTabView : MonoBehaviour, IHotfixable
{
	private Text m_typeText; // 0x18
	private GameObject m_selectGo; // 0x20
	private RectTransform m_rectTrans; // 0x28
	private GameObject m_goCount; // 0x30
	private GameObject m_goShu; // 0x38
	private Text m_lbCount; // 0x40
	private UISelectGroupTypeEvent m_listener; // 0x48
	private VoicelangTypeViewModel m_model; // 0x50
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_SetIsLastTab; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectEvent; // 0x10
	private static DelegateBridge __Hotfix0_SetWidth; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22a1a28 VA: 0x75948b9a28
	public Void UpdateView(VoicelangTypeViewModel model) { }
	// RVA: 0x22a1c64 VA: 0x75948b9c64
	public Void SetIsLastTab(Boolean isLast) { }
	// RVA: 0x22a1b44 VA: 0x75948b9b44
	public Void SetSelectEvent(UISelectGroupTypeEvent listener) { }
	// RVA: 0x22a1bc8 VA: 0x75948b9bc8
	public Void SetWidth(Single width) { }
	// RVA: 0x22a1dd8 VA: 0x75948b9dd8
	public Void OnClick() { }
	// RVA: 0x22a1e78 VA: 0x75948b9e78
	public Void .ctor() { }
}
```