# Act1ArcadeStageSelectBadgeItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Image _badgeIcon`

- `Image _badgeTier`

- `GameObject _panelLocked`

- `Int32 m_catchedTier`

- `String m_catchedBadgeId`


## Methods

- `Void Render(String, Act1ArcadeBadgeBookItemViewModel, ILoadAsset, Boolean)`

- `Void _TryRefreshBadgeIcon(String, Act1ArcadeBadgeBookItemViewModel, Act1ArcadeBadgeBookItemTierViewModel, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageSelectBadgeItemView : MonoBehaviour, IHotfixable
{
	private Image _badgeIcon; // 0x18
	private Image _badgeTier; // 0x20
	private GameObject _panelLocked; // 0x28
	private Int32 m_catchedTier; // 0x30
	private String m_catchedBadgeId; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__TryRefreshBadgeIcon; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3414c88 VA: 0x7595a2cc88
	public Void Render(String actId, Act1ArcadeBadgeBookItemViewModel badgeItemViewModel, ILoadAsset assetLoader, Boolean showTierShow) { }
	// RVA: 0x3414d9c VA: 0x7595a2cd9c
	private Void _TryRefreshBadgeIcon(String actId, Act1ArcadeBadgeBookItemViewModel badgeItemViewModel, Act1ArcadeBadgeBookItemTierViewModel tierModer, ILoadAsset assetLoader) { }
	// RVA: 0x3414f68 VA: 0x7595a2cf68
	public Void .ctor() { }
}
```