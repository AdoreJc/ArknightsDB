# UICharacterTrackPointFilterItem

**Namespace:** `Torappu.UI`


## Fields

- `Text _textCount`

- `UnityEvent _eventTrackPointFilterClick`

- `Boolean m_isInited`

- `TwoStateToggle m_twoStateToggle`


## Methods

- `Void SetCountText(Int32)`

- `Void _InitIfNot()`

- `Void _OnToggle(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterTrackPointFilterItem : DataBinder`1, IHotfixable
{
	private static readonly Color COLOR_SELECTED; // 0x0
	private static readonly Color COLOR_UNSELECTED; // 0x10
	private Text _textCount; // 0x20
	private UnityEvent _eventTrackPointFilterClick; // 0x28
	private Boolean m_isInited; // 0x30
	private TwoStateToggle m_twoStateToggle; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_SetCountText; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnToggle; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2138d7c VA: 0x7594750d7c
	public override Void OnValueChanged(BoolProperty property) { }
	// RVA: 0x2138c30 VA: 0x7594750c30
	public Void SetCountText(Int32 count) { }
	// RVA: 0x2138ea8 VA: 0x7594750ea8
	private Void _InitIfNot() { }
	// RVA: 0x2138fcc VA: 0x7594750fcc
	private Void _OnToggle(State state) { }
	// RVA: 0x2139070 VA: 0x7594751070
	public Void .ctor() { }
	// RVA: 0x2139110 VA: 0x7594751110
	private static Void .cctor() { }
}
```