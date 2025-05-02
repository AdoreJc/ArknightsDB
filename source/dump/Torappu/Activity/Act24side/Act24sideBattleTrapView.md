# Act24sideBattleTrapView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIAtlasObject _atlas`

- `UIAtlasImage _imgCurTakeCount`

- `SimpleLayoutContent _trapCardList`

- `SimpleLayoutContent _trapSmallIconList`

- `UIAnimationLocation _enterAnim`

- `Boolean m_hasInited`

- `TrapCardListAdapter m_trapCardListAdapter`

- `TrapSmallIconListAdapter m_trapSmallIconListAdapter`

- `Act24sideBattleTrapViewModel m_model`

- `UIStateFinder m_finder`


## Methods

- `Void PlayEnterAnim()`

- `Void _InitIfNot()`

- `SpriteRenderData _GetCurTakeCountSprite(Int32, Int32)`

- `Void EventOnConfirmClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapView : DataBinder`1
{
	private UIAtlasObject _atlas; // 0x20
	private UIAtlasImage _imgCurTakeCount; // 0x28
	private SimpleLayoutContent _trapCardList; // 0x30
	private SimpleLayoutContent _trapSmallIconList; // 0x38
	private UIAnimationLocation _enterAnim; // 0x40
	private Boolean m_hasInited; // 0x50
	private TrapCardListAdapter m_trapCardListAdapter; // 0x58
	private TrapSmallIconListAdapter m_trapSmallIconListAdapter; // 0x60
	private Act24sideBattleTrapViewModel m_model; // 0x68
	private UIStateFinder m_finder; // 0x70
	private const String IMG_TAKE_COUNT_PREFIX; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetCurTakeCountSprite; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3296eac VA: 0x75958aeeac
	public override Void OnValueChanged(Act24sideBattleTrapViewProperty property) { }
	// RVA: 0x3295b98 VA: 0x75958adb98
	public Void PlayEnterAnim() { }
	// RVA: 0x3296ff8 VA: 0x75958aeff8
	private Void _InitIfNot() { }
	// RVA: 0x329711c VA: 0x75958af11c
	private SpriteRenderData _GetCurTakeCountSprite(Int32 takeCount, Int32 maxCount) { }
	// RVA: 0x3297364 VA: 0x75958af364
	public Void EventOnConfirmClick() { }
	// RVA: 0x3297418 VA: 0x75958af418
	public Void .ctor() { }
}
```