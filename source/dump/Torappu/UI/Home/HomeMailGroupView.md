# HomeMailGroupView

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMailRecycleAdapter _dataTarget`

- `Text _textUnreadCount`

- `Text _textNoMails`

- `Text _mailCount`

- `LoopScrollRect _scrollRect`

- `Int32 m_cachedSequenceNum`

- `UIStateFinder m_stateFinder`

- `Int32 m_count`


## Methods

- `Void TryTriggerDrag()`

- `Void DealWithDrag(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailGroupView : DataBinder`1
{
	private HomeMailRecycleAdapter _dataTarget; // 0x20
	private Text _textUnreadCount; // 0x28
	private Text _textNoMails; // 0x30
	private Text _mailCount; // 0x38
	private LoopScrollRect _scrollRect; // 0x40
	private Int32 m_cachedSequenceNum; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private Int32 m_count; // 0x60
	private static DelegateBridge __Hotfix0_TryTriggerDrag; // 0x0
	private static DelegateBridge __Hotfix0_DealWithDrag; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2843a88 VA: 0x7594e5ba88
	public Void TryTriggerDrag() { }
	// RVA: 0x2843b04 VA: 0x7594e5bb04
	public Void DealWithDrag(Vector2 offset) { }
	// RVA: 0x2843c1c VA: 0x7594e5bc1c
	public override Void OnValueChanged(MailItemGroupViewProperty property) { }
	// RVA: 0x2843e9c VA: 0x7594e5be9c
	public Void .ctor() { }
}
```