# ZoneSanView

**Namespace:** ` `


## Fields

- `GameObject _pnlRoot`

- `Text _textSan`

- `Text _textZone`

- `UIAtlasImage _atlasLayerIcon`

- `UIAtlasImage _atlasLayerDot`

- `UIAtlasImage _imgLight`

- `RL02ReportSanView m_closure`


## Methods

- `Void Init(RL02ReportSanView)`

- `Void Render(ZoneSanInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ZoneSanView : IHotfixable
{
	private static Color COLOR_SAN_FULL; // 0x0
	private static Color COLOR_SAN_EMPTY; // 0x10
	private static Color COLOR_SAN_TEXT_EMPTY; // 0x20
	private static Color COLOR_SAN_TEXT_NORMAL; // 0x30
	private GameObject _pnlRoot; // 0x10
	private Text _textSan; // 0x18
	private Text _textZone; // 0x20
	private UIAtlasImage _atlasLayerIcon; // 0x28
	private UIAtlasImage _atlasLayerDot; // 0x30
	private UIAtlasImage _imgLight; // 0x38
	private RL02ReportSanView m_closure; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2b66a78 VA: 0x759517ea78
	public Void Init(RL02ReportSanView closure) { }
	// RVA: 0x2b66d74 VA: 0x759517ed74
	public Void Render(ZoneSanInfo sanInfo) { }
	// RVA: 0x2b671b0 VA: 0x759517f1b0
	public Void .ctor() { }
	// RVA: 0x2b67230 VA: 0x759517f230
	private static Void .cctor() { }
}
```