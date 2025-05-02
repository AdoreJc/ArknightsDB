# Act42D0RewardView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0RewardAreaView _areaView`

- `Act42D0RewardTitleView _titleView`

- `Act42D0RewardStageView _stageView`

- `Text _hint`

- `Text _desc`

- `Image _icon`

- `Sprite m_cachedSprite`


## Methods

- `Void _LoadIcon(String, String)`

- `Void _UnloadIconIfNot()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardView : DataBinder`1
{
	private Act42D0RewardAreaView _areaView; // 0x20
	private Act42D0RewardTitleView _titleView; // 0x28
	private Act42D0RewardStageView _stageView; // 0x30
	private Text _hint; // 0x38
	private Text _desc; // 0x40
	private Image _icon; // 0x48
	private Sprite m_cachedSprite; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__LoadIcon; // 0x8
	private static DelegateBridge __Hotfix0__UnloadIconIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32219c8 VA: 0x75958399c8
	public override Void OnValueChanged(Act42D0RewardProperty property) { }
	// RVA: 0x3221bc4 VA: 0x7595839bc4
	private Void _LoadIcon(String itemId, String iconId) { }
	// RVA: 0x3221d10 VA: 0x7595839d10
	private Void _UnloadIconIfNot() { }
	// RVA: 0x3221eb0 VA: 0x7595839eb0
	private Void OnDestroy() { }
	// RVA: 0x3221f18 VA: 0x7595839f18
	public Void .ctor() { }
}
```