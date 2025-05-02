# Act1ArcadeBadgeBookTierItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAtlasImage _titleBackgroundImage`

- `Color _titleNormalColor`

- `Color _titleLockedColor`

- `Image _tierIconImage`

- `Text _titleText`

- `Image _titleIconImage`

- `Boolean _hasUnlockedTitleIcon`

- `Boolean _hasPreservedTitleIcon`

- `Text _unlockDescText`

- `Color _unlockHighlightColor`

- `Text _descText`

- `Boolean _showDescWhileLocked`

- `Color _descNormalColor`

- `Color _descLockedColor`

- `GameObject _lockedPanel`

- `GameObject _unlockedPanel`

- `Boolean m_hasInited`

- `ILoadAsset m_iAssetLoader`

- `Int32 m_cachedTier`


## Methods

- `Void Render(String, Act1ArcadeBadgeBookItemTierViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookTierItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _titleBackgroundImage; // 0x18
	private Color _titleNormalColor; // 0x20
	private Color _titleLockedColor; // 0x30
	private Image _tierIconImage; // 0x40
	private Text _titleText; // 0x48
	private Image _titleIconImage; // 0x50
	private Boolean _hasUnlockedTitleIcon; // 0x58
	private Boolean _hasPreservedTitleIcon; // 0x59
	private Text _unlockDescText; // 0x60
	private Color _unlockHighlightColor; // 0x68
	private Text _descText; // 0x78
	private Boolean _showDescWhileLocked; // 0x80
	private Color _descNormalColor; // 0x84
	private Color _descLockedColor; // 0x94
	private GameObject _lockedPanel; // 0xa8
	private GameObject _unlockedPanel; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private ILoadAsset m_iAssetLoader; // 0xc0
	private Int32 m_cachedTier; // 0xc8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33f7784 VA: 0x7595a0f784
	public Void Render(String actId, Act1ArcadeBadgeBookItemTierViewModel model) { }
	// RVA: 0x33fa2dc VA: 0x7595a122dc
	private Void _InitIfNot() { }
	// RVA: 0x33fa604 VA: 0x7595a12604
	public Void .ctor() { }
}
```