# Act42d0ChallengeAreaButtonHolder

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Transform _buttonContainer`

- `Act42d0ChallengeAreaButton _btnPrefab`

- `String _stageId`

- `Act42d0ChallengeAreaButton m_cachedBtn`

- `Boolean m_isInited`


## Properties

- `String stageId`


## Methods

- `Void Render(Act42D0ChallengeStageViewModel, Boolean)`

- `String get_stageId()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0ChallengeAreaButtonHolder : MonoBehaviour, IHotfixable
{
	private Transform _buttonContainer; // 0x18
	private Act42d0ChallengeAreaButton _btnPrefab; // 0x20
	private String _stageId; // 0x28
	private Act42d0ChallengeAreaButton m_cachedBtn; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String stageId { get; }

	// RVA: 0x321a648 VA: 0x7595832648
	public Void Render(Act42D0ChallengeStageViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x321a910 VA: 0x7595832910
	public String get_stageId() { }
	// RVA: 0x321a790 VA: 0x7595832790
	private Void _InitIfNot() { }
	// RVA: 0x321a978 VA: 0x7595832978
	public Void .ctor() { }
}
```