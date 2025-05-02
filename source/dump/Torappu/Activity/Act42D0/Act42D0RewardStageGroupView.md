# Act42D0RewardStageGroupView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _code`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Act42D0RewardStageViewModel m_cachedViewModel`

- `Adapter m_adapter`

- `Int32 m_maxCount`


## Methods

- `Void Render(Act42D0RewardStageViewModel, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardStageGroupView : MonoBehaviour, IHotfixable
{
	private Text _code; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_isInited; // 0x28
	private Act42D0RewardStageViewModel m_cachedViewModel; // 0x30
	private Adapter m_adapter; // 0x38
	private Int32 m_maxCount; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x321edcc VA: 0x7595836dcc
	public Void Render(Act42D0RewardStageViewModel viewModel, Int32 maxCount) { }
	// RVA: 0x321eeac VA: 0x7595836eac
	private Void _InitIfNot() { }
	// RVA: 0x321f060 VA: 0x7595837060
	public Void .ctor() { }
}
```