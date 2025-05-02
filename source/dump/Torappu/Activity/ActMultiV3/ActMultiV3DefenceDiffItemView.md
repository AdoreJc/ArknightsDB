# ActMultiV3DefenceDiffItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _starCountPartGO`

- `GameObject _bestRecordPartGO`

- `Text _textBestRecord`

- `Text _textCaption`

- `Color _colorRecordUnselect`

- `Color _colorRecordSelect`

- `Color _colorCaptionUnselect`

- `Color _colorCaptionSelect`

- `Text _textScore`


## Methods

- `Void <>xLuaBaseProxy_OnRender()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3DefenceDiffItemView : ActMultiV3QuickMatchDiffItemView
{
	private GameObject _starCountPartGO; // 0x80
	private GameObject _bestRecordPartGO; // 0x88
	private Text _textBestRecord; // 0x90
	private Text _textCaption; // 0x98
	private Color _colorRecordUnselect; // 0xa0
	private Color _colorRecordSelect; // 0xb0
	private Color _colorCaptionUnselect; // 0xc0
	private Color _colorCaptionSelect; // 0xd0
	private Text _textScore; // 0xe0
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x31259c0 VA: 0x759573d9c0
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x3125a28 VA: 0x759573da28
	protected override Void OnRender() { }
	// RVA: 0x3125d6c VA: 0x759573dd6c
	public Void .ctor() { }
	// RVA: 0x3125e48 VA: 0x759573de48
	private Void <>xLuaBaseProxy_OnRender() { }
}
```