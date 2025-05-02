# UnbindGrantResponse

**Namespace:** `HGSDK`


## Fields

- `Int64 delete_request_ts`

- `Int64 delete_commit_ts`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class UnbindGrantResponse : APIV2ResponseBase
{
	public const Int32 STATUS_PHONE_ERROR; // 0x0
	public const Int32 STATUS_IDNAME_ERROR; // 0x0
	public Int64 delete_request_ts; // 0x18
	public Int64 delete_commit_ts; // 0x20


	// RVA: 0x2f2aa68 VA: 0x7595542a68
	public Void .ctor() { }
}
```