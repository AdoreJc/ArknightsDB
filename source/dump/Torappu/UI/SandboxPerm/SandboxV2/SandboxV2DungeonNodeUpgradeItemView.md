# SandboxV2DungeonNodeUpgradeItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _iconImage`

- `Color _iconActiveColor`

- `Color _iconInactiveColor`

- `UIAtlasImage _iconBackImage`

- `Color _iconBackActiveColor`

- `Color _iconBackInactiveColor`

- `Text _nameText`

- `Text _unlockDescText`

- `Color _unlockDescActiveColor`

- `Color _unlockDescInactiveColor`

- `Text _unlockEffectText`

- `Color _unlockEffectActiveColor`

- `Color _unlockEffectInactiveColor`

- `Color _headImageActiveColor`

- `Color _headImageInactiveColor`

- `Color _headTextActiveColor`

- `Color _headTextInactiveColor`

- `GameObject _inactivePanel`

- `GameObject _unlockTipsPanel`

- `Text _unlockTipsText`

- `GameObject _bkg`

- `ScrollRect _contentScrollRect`

- `String m_cachedUpdateId`

- `ILoadAsset <assetLoader>k__BackingField`

- `Action <workbenchEvent>k__BackingField`


## Properties

- `ILoadAsset assetLoader`

- `Action workbenchEvent`


## Methods

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `Action get_workbenchEvent()`

- `Void set_workbenchEvent(Action)`

- `Void OnWorkbenchEvent()`

- `Void Render(SandboxV2DungeonNodeUpgradeItemViewModel)`

- `GameObject TutorialOnly_GetTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeUpgradeItemView : MonoBehaviour, IHotfixable
{
	private Image _iconImage; // 0x18
	private Color _iconActiveColor; // 0x20
	private Color _iconInactiveColor; // 0x30
	private UIAtlasImage _iconBackImage; // 0x40
	private Color _iconBackActiveColor; // 0x48
	private Color _iconBackInactiveColor; // 0x58
	private Text _nameText; // 0x68
	private Text _unlockDescText; // 0x70
	private Color _unlockDescActiveColor; // 0x78
	private Color _unlockDescInactiveColor; // 0x88
	private Text _unlockEffectText; // 0x98
	private Color _unlockEffectActiveColor; // 0xa0
	private Color _unlockEffectInactiveColor; // 0xb0
	private UIAtlasImage[] _headImages; // 0xc0
	private Color _headImageActiveColor; // 0xc8
	private Color _headImageInactiveColor; // 0xd8
	private Text[] _headTexts; // 0xe8
	private Color _headTextActiveColor; // 0xf0
	private Color _headTextInactiveColor; // 0x100
	private GameObject[] _activePanels; // 0x110
	private GameObject _inactivePanel; // 0x118
	private GameObject _unlockTipsPanel; // 0x120
	private Text _unlockTipsText; // 0x128
	private GameObject _bkg; // 0x130
	private ScrollRect _contentScrollRect; // 0x138
	private String m_cachedUpdateId; // 0x140
	private ILoadAsset <assetLoader>k__BackingField; // 0x148
	private Action <workbenchEvent>k__BackingField; // 0x150
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x8
	private static DelegateBridge __Hotfix0_get_workbenchEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_workbenchEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnWorkbenchEvent; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_TutorialOnly_GetTutorialGo; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ILoadAsset assetLoader { get; set; }
	private Action workbenchEvent { get; set; }

	// RVA: 0x256b33c VA: 0x7594b8333c
	private ILoadAsset get_assetLoader() { }
	// RVA: 0x256b3a4 VA: 0x7594b833a4
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x256b428 VA: 0x7594b83428
	private Action get_workbenchEvent() { }
	// RVA: 0x256b490 VA: 0x7594b83490
	public Void set_workbenchEvent(Action value) { }
	// RVA: 0x256b514 VA: 0x7594b83514
	public Void OnWorkbenchEvent() { }
	// RVA: 0x256b5b0 VA: 0x7594b835b0
	public Void Render(SandboxV2DungeonNodeUpgradeItemViewModel itemModel) { }
	// RVA: 0x256bb08 VA: 0x7594b83b08
	public GameObject TutorialOnly_GetTutorialGo() { }
	// RVA: 0x256bb70 VA: 0x7594b83b70
	public Void .ctor() { }
}
```