# SocialGetCrisisV2View

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _crisisUsedTime`

- `SocialGetHeadIconView _charHeadIconPrefab`

- `Transform _charHeadIconContainer`

- `TwoStateToggle _highestScoreToggle`

- `Text _highestScoreText`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(SocialGetCrisisV2ViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SocialGetCrisisV2View : MonoBehaviour, IHotfixable
{
	private const Int32 ICON_COUNT; // 0x0
	private Text _crisisUsedTime; // 0x18
	private SocialGetHeadIconView _charHeadIconPrefab; // 0x20
	private Transform _charHeadIconContainer; // 0x28
	private TwoStateToggle _highestScoreToggle; // 0x30
	private Text _highestScoreText; // 0x38
	private Boolean m_hasInited; // 0x40
	private List`1 m_headIconList; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x246f628 VA: 0x7594a87628
	private Void _InitIfNot() { }
	// RVA: 0x246f788 VA: 0x7594a87788
	public Void Render(SocialGetCrisisV2ViewModel model) { }
	// RVA: 0x246fab4 VA: 0x7594a87ab4
	public Void .ctor() { }
}
```