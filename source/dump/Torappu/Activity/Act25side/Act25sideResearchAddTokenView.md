# Act25sideResearchAddTokenView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _maxAnim`

- `Text _currentCount`

- `Text _maxCount`

- `GameObject _upTip`

- `GameObject _maxTip`

- `Single _numAnimDelay`

- `Single _numDuration`

- `Sequence m_sequence`

- `Action onDismiss`


## Methods

- `Void Render(Int32, Int32, Int32, Boolean)`

- `Void _ShowAdd(Int32, Int32, Int32)`

- `Void _ShowMax(Int32)`

- `Void OnDismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchAddTokenView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _enterAnim; // 0x18
	private UIAnimationLocation _maxAnim; // 0x28
	private Text _currentCount; // 0x38
	private Text _maxCount; // 0x40
	private GameObject _upTip; // 0x48
	private GameObject _maxTip; // 0x50
	private Single _numAnimDelay; // 0x58
	private Single _numDuration; // 0x5c
	private Sequence m_sequence; // 0x60
	public Action onDismiss; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ShowAdd; // 0x8
	private static DelegateBridge __Hotfix0__ShowMax; // 0x10
	private static DelegateBridge __Hotfix0_OnDismiss; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3278b38 VA: 0x7595890b38
	public Void Render(Int32 initCount, Int32 addCount, Int32 maxCount, Boolean showMax) { }
	// RVA: 0x3281d30 VA: 0x7595899d30
	private Void _ShowAdd(Int32 initCount, Int32 addCount, Int32 maxCount) { }
	// RVA: 0x3281b7c VA: 0x7595899b7c
	private Void _ShowMax(Int32 maxCount) { }
	// RVA: 0x328205c VA: 0x759589a05c
	public Void OnDismiss() { }
	// RVA: 0x32820f4 VA: 0x759589a0f4
	public Void .ctor() { }
}
```