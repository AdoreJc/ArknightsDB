# SandboxV2DungeonNodeUpgradeView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backRect`

- `SimpleLayoutContent _itemLayout`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `ILoadAsset <assetLoader>k__BackingField`

- `Action <backEvent>k__BackingField`

- `Action <workbenchEvent>k__BackingField`


## Properties

- `ILoadAsset assetLoader`

- `Action backEvent`

- `Action workbenchEvent`


## Methods

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `Action get_backEvent()`

- `Void set_backEvent(Action)`

- `Action get_workbenchEvent()`

- `Void set_workbenchEvent(Action)`

- `Void OnBackEvent()`

- `Void _InitIfNot()`

- `GameObject TutorialOnly_GetTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeUpgradeView : DataBinder`1
{
	private RectTransform _backRect; // 0x20
	private SimpleLayoutContent _itemLayout; // 0x28
	private Boolean m_hasInited; // 0x30
	private Adapter m_adapter; // 0x38
	private List`1 m_cachedItems; // 0x40
	private ILoadAsset <assetLoader>k__BackingField; // 0x48
	private Action <backEvent>k__BackingField; // 0x50
	private Action <workbenchEvent>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x8
	private static DelegateBridge __Hotfix0_get_backEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_backEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_workbenchEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_workbenchEvent; // 0x28
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_TutorialOnly_GetTutorialGo; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private ILoadAsset assetLoader { get; set; }
	private Action backEvent { get; set; }
	private Action workbenchEvent { get; set; }

	// RVA: 0x256bbe0 VA: 0x7594b83be0
	private ILoadAsset get_assetLoader() { }
	// RVA: 0x256bc48 VA: 0x7594b83c48
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x256bccc VA: 0x7594b83ccc
	private Action get_backEvent() { }
	// RVA: 0x256bd34 VA: 0x7594b83d34
	public Void set_backEvent(Action value) { }
	// RVA: 0x256bdb8 VA: 0x7594b83db8
	private Action get_workbenchEvent() { }
	// RVA: 0x256be20 VA: 0x7594b83e20
	public Void set_workbenchEvent(Action value) { }
	// RVA: 0x256bea4 VA: 0x7594b83ea4
	public Void OnBackEvent() { }
	// RVA: 0x256bf40 VA: 0x7594b83f40
	public override Void OnValueChanged(SandboxV2DungeonNodeUpgradeProperty property) { }
	// RVA: 0x256c014 VA: 0x7594b84014
	private Void _InitIfNot() { }
	// RVA: 0x256c200 VA: 0x7594b84200
	public GameObject TutorialOnly_GetTutorialGo() { }
	// RVA: 0x256c390 VA: 0x7594b84390
	public Void .ctor() { }
}
```