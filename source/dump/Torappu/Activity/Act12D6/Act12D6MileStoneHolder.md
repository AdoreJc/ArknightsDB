# Act12D6MileStoneHolder

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Text _title`

- `LoopVerticalScrollRect _content`

- `Act12D6MileStoneGridAdapter _adapter`

- `Text _costText`

- `Button _btnFinishAll`

- `Int32 m_targetIndex`

- `String m_targetId`

- `Int32 m_max`

- `Boolean m_ableToGetFlag`


## Methods

- `Void RefreshInfo(List`1, Int32)`

- `Void RenderInfo(List`1, Int32)`

- `IEnumerator _RefreshTargetState(Single)`

- `Single <_RefreshTargetState>b__11_0()`

- `Void <_RefreshTargetState>b__11_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6MileStoneHolder : MonoBehaviour
{
	private Text _title; // 0x18
	private LoopVerticalScrollRect _content; // 0x20
	private Act12D6MileStoneGridAdapter _adapter; // 0x28
	private Text _costText; // 0x30
	private Button _btnFinishAll; // 0x38
	private Int32 m_targetIndex; // 0x40
	private String m_targetId; // 0x48
	private Int32 m_max; // 0x50
	private Boolean m_ableToGetFlag; // 0x54


	// RVA: 0x3472020 VA: 0x7595a8a020
	public Void RefreshInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x347145c VA: 0x7595a8945c
	public Void RenderInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x347c54c VA: 0x7595a9454c
	private IEnumerator _RefreshTargetState(Single index) { }
	// RVA: 0x347c5f8 VA: 0x7595a945f8
	public Void .ctor() { }
	// RVA: 0x347c60c VA: 0x7595a9460c
	private Single <_RefreshTargetState>b__11_0() { }
	// RVA: 0x347c628 VA: 0x7595a94628
	private Void <_RefreshTargetState>b__11_1(Single val) { }
}
```