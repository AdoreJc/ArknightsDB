# ArchiveQuestCgContentDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _mainImg`

- `UIDynImage _mainImgLoader`

- `String m_cachedCgId`

- `Tween m_tween`


## Methods

- `Void RefreshImage(SandboxV2ArchiveQuestCgData)`

- `String _GetCgPath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestCgContentDataBinder : DataBinder`1
{
	private Image _mainImg; // 0x20
	private UIDynImage _mainImgLoader; // 0x28
	private String m_cachedCgId; // 0x30
	private Tween m_tween; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_RefreshImage; // 0x8
	private static DelegateBridge __Hotfix0__GetCgPath; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x306e200 VA: 0x7595686200
	public override Void OnValueChanged(ArchiveQuestProperty property) { }
	// RVA: 0x306e310 VA: 0x7595686310
	private Void RefreshImage(SandboxV2ArchiveQuestCgData cgData) { }
	// RVA: 0x306e578 VA: 0x7595686578
	private String _GetCgPath(String cgPath) { }
	// RVA: 0x306e638 VA: 0x7595686638
	public Void .ctor() { }
}
```