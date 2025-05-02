# GameInOutObserver

**Namespace:** `Torappu`


## Fields

- `Manager m_mgr`

- `Callback m_callback`

- `Boolean <isInGame>k__BackingField`


## Properties

- `Boolean isInGame`


## Methods

- `Boolean get_isInGame()`

- `Void set_isInGame(Boolean)`

- `Boolean IsDisposed()`

- `Void Dispose()`

- `Void _SetIsInGame(Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class GameInOutObserver : IDisposable
{
	private Manager m_mgr; // 0x10
	private Callback m_callback; // 0x18
	private Boolean <isInGame>k__BackingField; // 0x20

	public Boolean isInGame { get; set; }

	// RVA: 0x674b460 VA: 0x7598d63460
	public Boolean get_isInGame() { }
	// RVA: 0x674b468 VA: 0x7598d63468
	private Void set_isInGame(Boolean value) { }
	// RVA: 0x674b474 VA: 0x7598d63474
	public Boolean IsDisposed() { }
	// RVA: 0x674b484 VA: 0x7598d63484
	public Void Dispose() { }
	// RVA: 0x674b530 VA: 0x7598d63530
	private Void .ctor(Manager mgr) { }
	// RVA: 0x674b560 VA: 0x7598d63560
	private Void _SetIsInGame(Boolean pIsInGame) { }
}
```