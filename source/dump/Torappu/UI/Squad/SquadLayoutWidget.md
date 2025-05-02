# SquadLayoutWidget

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _btnStartBattle`

- `GameObject _btnAssistFriend`

- `GridLayoutGroup _squadGrid`

- `RectTransform _middleGrid`

- `Int32 _addSquadPadding`

- `Int32 m_squadPaddingRaw`

- `Boolean m_isInited`

- `Boolean m_showPaddingCache`


## Methods

- `Void _InitIfNot()`

- `IEnumerator UpdateLayout(RectTransform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadLayoutWidget : DataBinder`1
{
	private GameObject _btnStartBattle; // 0x20
	private GameObject _btnAssistFriend; // 0x28
	private GridLayoutGroup _squadGrid; // 0x30
	private RectTransform _middleGrid; // 0x38
	private Int32 _addSquadPadding; // 0x40
	private Int32 m_squadPaddingRaw; // 0x44
	private Boolean m_isInited; // 0x48
	private Boolean m_showPaddingCache; // 0x49
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_UpdateLayout; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23ccea8 VA: 0x75949e4ea8
	private Void _InitIfNot() { }
	// RVA: 0x23ccf3c VA: 0x75949e4f3c
	public override Void OnValueChanged(SquadLayoutProperty property) { }
	// RVA: 0x23cd110 VA: 0x75949e5110
	private IEnumerator UpdateLayout(RectTransform rect) { }
	// RVA: 0x23cd1f8 VA: 0x75949e51f8
	public Void .ctor() { }
}
```