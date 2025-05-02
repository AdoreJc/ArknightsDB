# Act5D1DataHolder

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Action m_actionWhenHaveData`

- `Boolean m_isCrossDay`


## Properties

- `Act5D1Data actData`


## Methods

- `Act5D1Data get_actData()`

- `Void RefreshActData(Action)`

- `Void _TrySendDataRequest()`

- `Void <_TrySendDataRequest>b__9_0(Act5D1GetDetailResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1DataHolder : ActivityStageSingleComponent
{
	private Action m_actionWhenHaveData; // 0x20
	private ActivityDataFromServer`1 m_wrappedData; // 0x28
	private ResultHandler`1 m_dataRequest; // 0x30
	private Boolean m_isCrossDay; // 0x38
	private static DelegateBridge __Hotfix0_get_actDataWrapper; // 0x0
	private static DelegateBridge __Hotfix0_get_actData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshActData; // 0x10
	private static DelegateBridge __Hotfix0__TrySendDataRequest; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected ActivityDataFromServer`1 actDataWrapper { get; }
	public Act5D1Data actData { get; }

	// RVA: 0x31c3558 VA: 0x75957db558
	protected ActivityDataFromServer`1 get_actDataWrapper() { }
	// RVA: 0x31c3708 VA: 0x75957db708
	public Act5D1Data get_actData() { }
	// RVA: 0x31c3794 VA: 0x75957db794
	public Void RefreshActData(Action actionWhenHaveData) { }
	// RVA: 0x31c3924 VA: 0x75957db924
	private Void _TrySendDataRequest() { }
	// RVA: 0x31c3c20 VA: 0x75957dbc20
	public Void .ctor() { }
	// RVA: 0x31c3c90 VA: 0x75957dbc90
	private Void <_TrySendDataRequest>b__9_0(Act5D1GetDetailResponse response) { }
}
```