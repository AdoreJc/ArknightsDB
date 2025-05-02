# WebHttpResult

**Namespace:** `Torappu.Network`


## Fields

- `Boolean m_isCanceled`

- `Action onCanceled`

- `Boolean forceNotSecured`


## Properties

- `Boolean isCanceled`


## Methods

- `Boolean get_isCanceled()`

- `Void Cancel()`

- `Void NetworkerOnlyMarkCanceled()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class WebHttpResult
{
	private Boolean m_isCanceled; // 0x10
	public Action`1 response; // 0x18
	public Func`3 beforeRequest; // 0x20
	public Action onCanceled; // 0x28
	public Boolean forceNotSecured; // 0x30

	public Boolean isCanceled { get; }

	// RVA: 0x67b4584 VA: 0x7598dcc584
	public Boolean get_isCanceled() { }
	// RVA: 0x67b458c VA: 0x7598dcc58c
	public Void Cancel() { }
	// RVA: 0x67b2634 VA: 0x7598dca634
	public Void NetworkerOnlyMarkCanceled() { }
	// RVA: 0x67aefe0 VA: 0x7598dc6fe0
	public Void .ctor() { }
}
```