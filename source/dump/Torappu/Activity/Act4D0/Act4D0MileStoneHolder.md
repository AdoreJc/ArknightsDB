# Act4D0MileStoneHolder

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Text _title`

- `LoopVerticalScrollRect _content`

- `Act4D0MileStoneGridAdapter _adapter`

- `Image _backImage`

- `Text _costText`

- `Text _remainTime`

- `Boolean _skinReward`

- `Int32 m_targetIndex`

- `String m_targetId`

- `Int32 m_max`


## Methods

- `Void RefreshInfo(List`1, Int32)`

- `Void RenderInfo(List`1, Int32)`

- `Void DropToChar()`

- `IEnumerator _RefreshTargetState(Single)`

- `Single <_RefreshTargetState>b__13_0()`

- `Void <_RefreshTargetState>b__13_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0MileStoneHolder : MonoBehaviour
{
	private Text _title; // 0x18
	private LoopVerticalScrollRect _content; // 0x20
	private Act4D0MileStoneGridAdapter _adapter; // 0x28
	private Image _backImage; // 0x30
	private Text _costText; // 0x38
	private Text _remainTime; // 0x40
	private Boolean _skinReward; // 0x48
	private Int32 m_targetIndex; // 0x4c
	private String m_targetId; // 0x50
	private Int32 m_max; // 0x58


	// RVA: 0x31de328 VA: 0x75957f6328
	public Void RefreshInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x31dd100 VA: 0x75957f5100
	public Void RenderInfo(List`1 viewModelList, Int32 count) { }
	// RVA: 0x31e2088 VA: 0x75957fa088
	public Void DropToChar() { }
	// RVA: 0x31e2004 VA: 0x75957fa004
	private IEnumerator _RefreshTargetState(Single index) { }
	// RVA: 0x31e2244 VA: 0x75957fa244
	public Void .ctor() { }
	// RVA: 0x31e2258 VA: 0x75957fa258
	private Single <_RefreshTargetState>b__13_0() { }
	// RVA: 0x31e2274 VA: 0x75957fa274
	private Void <_RefreshTargetState>b__13_1(Single val) { }
}
```