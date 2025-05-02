# UICharacterStarMarkTopItemBinder

**Namespace:** `Torappu.UI`


## Fields

- `Transform _starMarkToggleContainer`

- `UICharacterStarMarkTopSortItem _starMarkTogglePrefab`

- `UIAnimationLocation _redPointContainerAnim`

- `UIAnimationLocation _topbarBgAnim`

- `UnityEvent _eventStarMarkTopClick`

- `UnityEvent _eventEnterStarMarkEditMode`

- `Boolean m_isInited`

- `UICharacterStarMarkTopSortItem m_starMarkToggle`

- `AnimationSwitchTween m_redPointSwitchAnim`

- `AnimationSwitchTween m_topbarToStarMarkTopSwitchAnim`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterStarMarkTopItemBinder : DataBinder`1, IHotfixable
{
	private Transform _starMarkToggleContainer; // 0x20
	private UICharacterStarMarkTopSortItem _starMarkTogglePrefab; // 0x28
	private UIAnimationLocation _redPointContainerAnim; // 0x30
	private UIAnimationLocation _topbarBgAnim; // 0x40
	private UnityEvent _eventStarMarkTopClick; // 0x50
	private UnityEvent _eventEnterStarMarkEditMode; // 0x58
	private Boolean m_isInited; // 0x60
	private UICharacterStarMarkTopSortItem m_starMarkToggle; // 0x68
	private AnimationSwitchTween m_redPointSwitchAnim; // 0x70
	private AnimationSwitchTween m_topbarToStarMarkTopSwitchAnim; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x21368f4 VA: 0x759474e8f4
	private Void _InitIfNot() { }
	// RVA: 0x2136cb4 VA: 0x759474ecb4
	public override Void OnValueChanged(BoolProperty property) { }
	// RVA: 0x2136ebc VA: 0x759474eebc
	public Void .ctor() { }
}
```