# SandboxV2BuildingTipView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _noticeInfo`

- `Text _noticeCount`

- `UIAtlasImage _bkgImage`

- `UIAtlasImage _imgSevereDamaged`

- `UIAtlasImage _imgBuildingDamaged`

- `UIAtlasImage _imgBuildingCanUpgrade`

- `CanvasGroup _canvasGroup`

- `SandboxV2ConstructTipType m_cachedTipType`


## Methods

- `Void Render(Param)`

- `Void _SetIcons(SandboxV2ConstructTipType)`

- `Void _SetTipText(SandboxV2ConstructTipType, String)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BuildingTipView : MonoBehaviour, IHotfixable
{
	private Text _noticeInfo; // 0x18
	private Text _noticeCount; // 0x20
	private UIAtlasImage _bkgImage; // 0x28
	private UIAtlasImage _imgSevereDamaged; // 0x30
	private UIAtlasImage _imgBuildingDamaged; // 0x38
	private UIAtlasImage _imgBuildingCanUpgrade; // 0x40
	private Color[] _foregroundSelectedColors; // 0x48
	private Color[] _foregroundUnselectedColors; // 0x50
	private Color[] _bkgSelectedColors; // 0x58
	private Color[] _bkgUnselectedColors; // 0x60
	private CanvasGroup _canvasGroup; // 0x68
	private SandboxV2ConstructTipType m_cachedTipType; // 0x70
	private Action`1 m_onClicked; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetIcons; // 0x8
	private static DelegateBridge __Hotfix0__SetTipText; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24fd89c VA: 0x7594b1589c
	public Void Render(Param param) { }
	// RVA: 0x24fdb08 VA: 0x7594b15b08
	private Void _SetIcons(SandboxV2ConstructTipType tipType) { }
	// RVA: 0x24fdbe4 VA: 0x7594b15be4
	private Void _SetTipText(SandboxV2ConstructTipType tipType, String nodeTypeName) { }
	// RVA: 0x24fdd84 VA: 0x7594b15d84
	public Void OnClicked() { }
	// RVA: 0x24fde0c VA: 0x7594b15e0c
	public Void .ctor() { }
}
```