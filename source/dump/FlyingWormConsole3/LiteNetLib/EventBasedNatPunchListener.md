# EventBasedNatPunchListener

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `OnNatIntroductionRequest NatIntroductionRequest`

- `OnNatIntroductionSuccess NatIntroductionSuccess`


## Methods

- `Void add_NatIntroductionRequest(OnNatIntroductionRequest)`

- `Void remove_NatIntroductionRequest(OnNatIntroductionRequest)`

- `Void add_NatIntroductionSuccess(OnNatIntroductionSuccess)`

- `Void remove_NatIntroductionSuccess(OnNatIntroductionSuccess)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public class EventBasedNatPunchListener : INatPunchListener
{
	private OnNatIntroductionRequest NatIntroductionRequest; // 0x10
	private OnNatIntroductionSuccess NatIntroductionSuccess; // 0x18


	// RVA: 0x40f75c0 VA: 0x759670f5c0
	public Void add_NatIntroductionRequest(OnNatIntroductionRequest value) { }
	// RVA: 0x40f765c VA: 0x759670f65c
	public Void remove_NatIntroductionRequest(OnNatIntroductionRequest value) { }
	// RVA: 0x40f76f8 VA: 0x759670f6f8
	public Void add_NatIntroductionSuccess(OnNatIntroductionSuccess value) { }
	// RVA: 0x40f7794 VA: 0x759670f794
	public Void remove_NatIntroductionSuccess(OnNatIntroductionSuccess value) { }
	// RVA: 0x40f7830 VA: 0x759670f830
	private Void FlyingWormConsole3.LiteNetLib.INatPunchListener.OnNatIntroductionRequest(IPEndPoint localEndPoint, IPEndPoint remoteEndPoint, String token) { }
	// RVA: 0x40f784c VA: 0x759670f84c
	private Void FlyingWormConsole3.LiteNetLib.INatPunchListener.OnNatIntroductionSuccess(IPEndPoint targetEndPoint, NatAddressType type, String token) { }
	// RVA: 0x40f7868 VA: 0x759670f868
	public Void .ctor() { }
}
```