# AssistAssistantContainer

**Namespace:** `Torappu.Building.UI.Assist`


## Fields

- `AssistAssistantView _assistView`


## Methods

- `Void set_onAssistSlotClicked(Action`1)`

- `Void Render()`

- `Void _ReloadAssistViews()`

- `Void _OnAssistSlotClicked(Int32)`

- `Void _TryRegisterAVGSlots(IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Assist
public class AssistAssistantContainer : MonoBehaviour
{
	private AssistAssistantView _assistView; // 0x18
	private Transform[] _assistContainer; // 0x20
	private List`1 m_assistInsts; // 0x28
	private Action`1 <onAssistSlotClicked>k__BackingField; // 0x30

	private Action`1 onAssistSlotClicked { get; set; }

	// RVA: 0x3e32974 VA: 0x759644a974
	private Action`1 get_onAssistSlotClicked() { }
	// RVA: 0x3e3297c VA: 0x759644a97c
	public Void set_onAssistSlotClicked(Action`1 value) { }
	// RVA: 0x3e309d4 VA: 0x75964489d4
	public Void Render() { }
	// RVA: 0x3e32984 VA: 0x759644a984
	private Void _ReloadAssistViews() { }
	// RVA: 0x3e33604 VA: 0x759644b604
	private Void _OnAssistSlotClicked(Int32 index) { }
	// RVA: 0x3e3337c VA: 0x759644b37c
	private Void _TryRegisterAVGSlots(IList`1 assistSlots) { }
	// RVA: 0x3e33620 VA: 0x759644b620
	public Void .ctor() { }
}
```