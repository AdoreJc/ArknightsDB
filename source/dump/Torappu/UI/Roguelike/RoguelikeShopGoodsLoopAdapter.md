# RoguelikeShopGoodsLoopAdapter

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeGoodsObjView _goodsPrefab`

- `Single _maxTweenTime`

- `Boolean m_hasInited`

- `SwitchPlayHandler m_switchPlayHandler`

- `Boolean m_isShow`

- `Boolean m_fastMode`

- `Tween m_playTween`

- `Single m_progress`

- `Single m_offset`

- `Single m_range`

- `Single m_fixItemDuration`

- `RoguelikeShopLineupControllerBindings <controllerBindings>k__BackingField`


## Properties

- `RoguelikeShopLineupControllerBindings controllerBindings`


## Methods

- `RoguelikeShopLineupControllerBindings get_controllerBindings()`

- `Void set_controllerBindings(RoguelikeShopLineupControllerBindings)`

- `Single PlaySwitch(Boolean, Boolean)`

- `Single _GetProgress()`

- `Void _SetProgress(Single)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopGoodsLoopAdapter : LoopScrollAdapter`2
{
	private RoguelikeGoodsObjView _goodsPrefab; // 0x58
	private Single _maxTweenTime; // 0x60
	private Boolean m_hasInited; // 0x64
	private SwitchPlayHandler m_switchPlayHandler; // 0x68
	private Boolean m_isShow; // 0x70
	private Boolean m_fastMode; // 0x71
	private Tween m_playTween; // 0x78
	private Single m_progress; // 0x80
	private Single m_offset; // 0x84
	private Single m_range; // 0x88
	private Single m_fixItemDuration; // 0x8c
	private RoguelikeShopLineupControllerBindings <controllerBindings>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_controllerBindings; // 0x0
	private static DelegateBridge __Hotfix0_set_controllerBindings; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_PlaySwitch; // 0x20
	private static DelegateBridge __Hotfix0__GetProgress; // 0x28
	private static DelegateBridge __Hotfix0__SetProgress; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private RoguelikeShopLineupControllerBindings controllerBindings { get; set; }

	// RVA: 0x2ae8ff8 VA: 0x7595100ff8
	private RoguelikeShopLineupControllerBindings get_controllerBindings() { }
	// RVA: 0x2ae9060 VA: 0x7595101060
	public Void set_controllerBindings(RoguelikeShopLineupControllerBindings value) { }
	// RVA: 0x2ae90e4 VA: 0x75951010e4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2ae91e0 VA: 0x75951011e0
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, RoguelikeGoodsViewModel data) { }
	// RVA: 0x2ae95d8 VA: 0x75951015d8
	public Single PlaySwitch(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2ae99f8 VA: 0x75951019f8
	private Single _GetProgress() { }
	// RVA: 0x2ae9a60 VA: 0x7595101a60
	private Void _SetProgress(Single progress) { }
	// RVA: 0x2ae94b4 VA: 0x75951014b4
	private Void _InitIfNot() { }
	// RVA: 0x2ae9b70 VA: 0x7595101b70
	public Void .ctor() { }
}
```