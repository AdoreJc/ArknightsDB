# HomeMailStateBean

**Namespace:** `Torappu.UI.Home`


## Fields

- `MailTitleViewProperty mailTitleViewProperty`

- `MailItemGroupViewProperty mailGroupProperty`


## Methods

- `MailItemViewModel GetMail(HomeMailIndex)`

- `MailMetaInfo GetMeta(HomeMailIndex)`

- `Void ReceiveMail(HomeMailIndex)`

- `Void GetMetaList(GetMetaInfoListResponse)`

- `Void GetDataByIndex(Int32, Int32, ListMailBoxResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public MailTitleViewProperty mailTitleViewProperty; // 0x18
	public MailItemGroupViewProperty mailGroupProperty; // 0x20
	private static DelegateBridge __Hotfix0_GetMail; // 0x0
	private static DelegateBridge __Hotfix0_GetMeta; // 0x8
	private static DelegateBridge __Hotfix0_ParseReceiveItemResponseToViewModel; // 0x10
	private static DelegateBridge __Hotfix0_ReceiveMail; // 0x18
	private static DelegateBridge __Hotfix0_GetMetaList; // 0x20
	private static DelegateBridge __Hotfix0_GetDataByIndex; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x281e640 VA: 0x7594e36640
	public MailItemViewModel GetMail(HomeMailIndex indexId) { }
	// RVA: 0x281e820 VA: 0x7594e36820
	public MailMetaInfo GetMeta(HomeMailIndex indexId) { }
	// RVA: 0x281e9cc VA: 0x7594e369cc
	public static UIItemViewModel ParseReceiveItemResponseToViewModel(MailGet mailGet) { }
	// RVA: 0x281ea90 VA: 0x7594e36a90
	public Void ReceiveMail(HomeMailIndex mailIndex) { }
	// RVA: 0x281eb9c VA: 0x7594e36b9c
	public Void GetMetaList(GetMetaInfoListResponse response) { }
	// RVA: 0x281ecec VA: 0x7594e36cec
	public Void GetDataByIndex(Int32 startIndex, Int32 endIndex, ListMailBoxResponse response) { }
	// RVA: 0x281f6c8 VA: 0x7594e376c8
	public Void .ctor() { }
}
```