# ActMultiV3NormalMatchDiffItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _starCountPartGO`

- `Text _textStar`


## Methods

- `Void <>xLuaBaseProxy_OnRender()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3NormalMatchDiffItemView : ActMultiV3QuickMatchDiffItemView
{
	private GameObject _starCountPartGO; // 0x80
	private Text _textStar; // 0x88
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x3127ee8 VA: 0x759573fee8
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x3127f50 VA: 0x759573ff50
	protected override Void OnRender() { }
	// RVA: 0x3128144 VA: 0x7595740144
	public Void .ctor() { }
	// RVA: 0x31281b0 VA: 0x75957401b0
	private Void <>xLuaBaseProxy_OnRender() { }
}
```