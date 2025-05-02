# ArchivePicContentDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _mainImg`

- `UIDynImage _mainImgLoader`

- `Text _mainImgDesc`

- `GameObject _kvSetPanel`

- `Button _btnSetKV`

- `String m_cachedPicItem`

- `ArchivePicModel m_cachedModel`

- `Tween m_tween`


## Methods

- `Void _RefreshLeftImage(Boolean)`

- `String _GetPicPath(PicArchiveResItemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchivePicContentDataBinder : DataBinder`1
{
	private Image _mainImg; // 0x20
	private UIDynImage _mainImgLoader; // 0x28
	private Text _mainImgDesc; // 0x30
	private GameObject _kvSetPanel; // 0x38
	private Button _btnSetKV; // 0x40
	private String m_cachedPicItem; // 0x48
	private ArchivePicModel m_cachedModel; // 0x50
	private Tween m_tween; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RefreshLeftImage; // 0x8
	private static DelegateBridge __Hotfix0__GetPicPath; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3068f04 VA: 0x7595680f04
	public override Void OnValueChanged(PicProperty property) { }
	// RVA: 0x3068ff4 VA: 0x7595680ff4
	private Void _RefreshLeftImage(Boolean samePic) { }
	// RVA: 0x3069460 VA: 0x7595681460
	private String _GetPicPath(PicArchiveResItemData picItemData) { }
	// RVA: 0x306955c VA: 0x759568155c
	public Void .ctor() { }
}
```