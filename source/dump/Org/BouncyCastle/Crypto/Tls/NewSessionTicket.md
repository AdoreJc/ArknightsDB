# NewSessionTicket

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class NewSessionTicket
{
	protected readonly Int64 mTicketLifetimeHint; // 0x10
	protected readonly Byte[] mTicket; // 0x18

	public virtual Int64 TicketLifetimeHint { get; }
	public virtual Byte[] Ticket { get; }

	// RVA: 0x64daa88 VA: 0x7598af2a88
	public Void .ctor(Int64 ticketLifetimeHint, Byte[] ticket) { }
	// RVA: 0x64e568c VA: 0x7598afd68c
	public virtual Int64 get_TicketLifetimeHint() { }
	// RVA: 0x64e5694 VA: 0x7598afd694
	public virtual Byte[] get_Ticket() { }
	// RVA: 0x64e569c VA: 0x7598afd69c
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e5718 VA: 0x7598afd718
	public static NewSessionTicket Parse(Stream input) { }
}
```