# MockDIYRoomInfoManager

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `MockDIYRoomTemplateDB _templateDB`


## Methods

- `Void Awake()`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYRoomInfoManager : MonoBehaviour, IDIYRoomInfoProvider
{
	private String[] _templateIds; // 0x18
	private MockDIYRoomTemplateDB _templateDB; // 0x20
	private List`1 m_DIYRoomInfoList; // 0x28


	// RVA: 0x37f3514 VA: 0x7595e0b514
	private Void Awake() { }
	// RVA: 0x37f08fc VA: 0x7595e088fc
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37ee3a4 VA: 0x7595e063a4
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37f37bc VA: 0x7595e0b7bc
	public Void .ctor() { }
}
```