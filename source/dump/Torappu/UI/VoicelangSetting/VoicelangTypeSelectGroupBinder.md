# VoicelangTypeSelectGroupBinder

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `RectTransform m_tabRoot`

- `VoicelangTypeTabView m_prefab`

- `UISelectGroupTypeEvent m_onClick`

- `Boolean m_isInited`

- `Single groupSize`


## Methods

- `Void _InitIfNot(VoicelangTypeSelectGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangTypeSelectGroupBinder : DataBinder`1, IHotfixable
{
	private RectTransform m_tabRoot; // 0x20
	private VoicelangTypeTabView m_prefab; // 0x28
	private UISelectGroupTypeEvent m_onClick; // 0x30
	private List`1 viewList; // 0x38
	private Boolean m_isInited; // 0x40
	private Single groupSize; // 0x44
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22a1634 VA: 0x75948b9634
	public override Void OnValueChanged(VoicelangTypeSelectGroupViewProperty property) { }
	// RVA: 0x22a1874 VA: 0x75948b9874
	private Void _InitIfNot(VoicelangTypeSelectGroupViewProperty property) { }
	// RVA: 0x22a1cec VA: 0x75948b9cec
	public Void .ctor() { }
}
```