# Retrieve Inquiry Status

## Request

**Method**: GET

**Path**: /inquiries/:inquiryNumber:/status

**Parameters**:
| Name | Type | Description |
|---|---|---|
|inquiryNumber|string|the inquiry number|

**Headers**:

**optional:** these headers will only be included for users that are logged in

| Name | Type | Description |
|---|---|---|
|Authorization|JWT?|Token for access to the CRM API|
|ICN|string|The logged in user's ICN|

## Response

<table>
<tr>
<td> Status </td> <td> Response </td>
</tr>
<tr>
<td> 200 </td>
<td>

```json
{ 
    "status": { 
        "code": 200, 
        "message": "OK", 
        "data": {
          "inquiryNumber": "A-123456",
          "inquiryStatus": "In Progress",
          "inquiryRecordStatus": "active"
        }
    }
}
```

</td>
</tr>
<tr>
<td> 404 </td>
<td>

```json
{ 
    "status": { 
        "code": 404, 
        "message": "Inquiry Not Found"
    }
}
```

</td>
</tr>
</table>

## Notes

The data returned is the same structure as the dashboard list of inquiries, but will contain the one inquiry that matches the inquiry number provided.
