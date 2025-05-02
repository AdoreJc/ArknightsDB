# GrantInfoResponse

**Namespace:** `HGSDK`


## Fields

- `String uid`

- `Int64 delete_request_ts`

- `Int64 delete_commit_ts`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class GrantInfoResponse : APIV2ResponseBase
{
	public const Int32 STATUS_ALREADY_UNBIND; // 0x0
	public String uid; // 0x18
	public Int64 delete_request_ts; // 0x20
	public Int64 delete_commit_ts; // 0x28


	// RVA: 0x2f2aa78 VA: 0x7595542a78
	public Void .ctor() { }
}
```