# DefaultGroupManager

**Namespace:** `UnityEngine.UIElements`


## Fields

- `IGroupBoxOption m_SelectedOption`


## Methods

- `Void OnOptionSelectionChanged(IGroupBoxOption)`

- `Void RegisterOption(IGroupBoxOption)`

- `Void UnregisterOption(IGroupBoxOption)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DefaultGroupManager : IGroupManager
{
	private List`1 m_GroupOptions; // 0x10
	private IGroupBoxOption m_SelectedOption; // 0x18


	// RVA: 0x69392c4 VA: 0x7598f512c4
	public Void OnOptionSelectionChanged(IGroupBoxOption selectedOption) { }
	// RVA: 0x69394a4 VA: 0x7598f514a4
	public Void RegisterOption(IGroupBoxOption option) { }
	// RVA: 0x693958c VA: 0x7598f5158c
	public Void UnregisterOption(IGroupBoxOption option) { }
	// RVA: 0x6938dfc VA: 0x7598f50dfc
	public Void .ctor() { }
}
```