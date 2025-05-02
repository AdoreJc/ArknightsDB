# ActMultiV3FootballDiffItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _bestRecordPartGO`

- `Text _textBestRecord`

- `Text _textCaption`

- `Color _colorRecordUnselect`

- `Color _colorRecordSelect`

- `Color _colorCaptionUnselect`

- `Color _colorCaptionSelect`


## Methods

- `Void <>xLuaBaseProxy_OnRender()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3FootballDiffItemView : ActMultiV3QuickMatchDiffItemView
{
	private GameObject _bestRecordPartGO; // 0x80
	private Text _textBestRecord; // 0x88
	private Text _textCaption; // 0x90
	private Color _colorRecordUnselect; // 0x98
	private Color _colorRecordSelect; // 0xa8
	private Color _colorCaptionUnselect; // 0xb8
	private Color _colorCaptionSelect; // 0xc8
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x3125eb0 VA: 0x759573deb0
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x3125f18 VA: 0x759573df18
	protected override Void OnRender() { }
	// RVA: 0x31260d8 VA: 0x759573e0d8
	public Void .ctor() { }
	// RVA: 0x3126144 VA: 0x759573e144
	private Void <>xLuaBaseProxy_OnRender() { }
}
```