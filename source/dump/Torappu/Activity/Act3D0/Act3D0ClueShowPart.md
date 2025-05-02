# Act3D0ClueShowPart

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Text _remainCount`

- `GameObject _haveRemainCount`

- `Animator _haveAnimator`

- `Text _currentText`

- `Image _clueBackImg`

- `Int32 m_remainCount`


## Methods

- `Void InitRender()`

- `Void AddNewClue(String)`

- `Void OpenClue()`

- `Void _RenderClue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0ClueShowPart : MonoBehaviour, IHotfixable
{
	private Text _remainCount; // 0x18
	private GameObject _haveRemainCount; // 0x20
	private Animator _haveAnimator; // 0x28
	private Text _currentText; // 0x30
	private Image _clueBackImg; // 0x38
	private Int32 m_remainCount; // 0x40
	private static DelegateBridge __Hotfix0_InitRender; // 0x0
	private static DelegateBridge __Hotfix0_AddNewClue; // 0x8
	private static DelegateBridge __Hotfix0_OpenClue; // 0x10
	private static DelegateBridge __Hotfix0__RenderClue; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x322fafc VA: 0x7595847afc
	public Void InitRender() { }
	// RVA: 0x3230300 VA: 0x7595848300
	public Void AddNewClue(String clueId) { }
	// RVA: 0x322fce0 VA: 0x7595847ce0
	public Void OpenClue() { }
	// RVA: 0x32386d8 VA: 0x75958506d8
	private Void _RenderClue() { }
	// RVA: 0x32387a4 VA: 0x75958507a4
	public Void .ctor() { }
}
```