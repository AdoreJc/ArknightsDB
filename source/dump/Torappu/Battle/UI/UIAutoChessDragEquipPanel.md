# UIAutoChessDragEquipPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollower _follower`

- `UIAnimationLocation _beginAnim`

- `UIAnimationLocation _endAnim`

- `UIAnimationLocation _leftAnim`

- `UIAnimationLocation _rightAnim`

- `Transform _normalFrame`

- `Transform _fullFrame`

- `Transform _fullMatte`

- `Image _leftNormalGroup`

- `Transform _leftEmptyGroup`

- `Image _rightNormalGroup`

- `Transform _rightEmptyGroup`

- `Boolean m_isHide`

- `Tween m_tween`


## Methods

- `Void Render(Param)`

- `Sprite _GetEquipIconSprite(Int32)`

- `Void Hide()`

- `Void _PlayAnimLocationIfNotActive(UIAnimationLocation, TweenCallback)`

- `Void EquipCharacter(Int32, TweenCallback)`

- `Void OnDestroy()`

- `Void _FinishTweenIfNot(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIAutoChessDragEquipPanel : MonoBehaviour, IHotfixable
{
	private UIFollower _follower; // 0x18
	private UIAnimationLocation _beginAnim; // 0x20
	private UIAnimationLocation _endAnim; // 0x30
	private UIAnimationLocation _leftAnim; // 0x40
	private UIAnimationLocation _rightAnim; // 0x50
	private Transform _normalFrame; // 0x60
	private Transform _fullFrame; // 0x68
	private Transform _fullMatte; // 0x70
	private Image _leftNormalGroup; // 0x78
	private Transform _leftEmptyGroup; // 0x80
	private Image _rightNormalGroup; // 0x88
	private Transform _rightEmptyGroup; // 0x90
	private Boolean m_isHide; // 0x98
	private List`1 m_equipInstIds; // 0xa0
	private Tween m_tween; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetEquipIconSprite; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimLocationIfNotActive; // 0x18
	private static DelegateBridge __Hotfix0_EquipCharacter; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__FinishTweenIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x201f528 VA: 0x7594637528
	public Void Render(Param param) { }
	// RVA: 0x201f904 VA: 0x7594637904
	private Sprite _GetEquipIconSprite(Int32 index) { }
	// RVA: 0x201fa7c VA: 0x7594637a7c
	public Void Hide() { }
	// RVA: 0x201f800 VA: 0x7594637800
	private Void _PlayAnimLocationIfNotActive(UIAnimationLocation location, TweenCallback callback) { }
	// RVA: 0x201fc1c VA: 0x7594637c1c
	public Void EquipCharacter(Int32 equipCnt, TweenCallback callback) { }
	// RVA: 0x201fcb4 VA: 0x7594637cb4
	private Void OnDestroy() { }
	// RVA: 0x201fb4c VA: 0x7594637b4c
	private Void _FinishTweenIfNot(Boolean completeTween) { }
	// RVA: 0x201fd20 VA: 0x7594637d20
	public Void .ctor() { }
}
```