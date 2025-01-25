[Admin Docs](/)

***

# Variable: mutationUpdateCurrentUserInputSchema

> `const` **mutationUpdateCurrentUserInputSchema**: `ZodEffects`\<`ZodObject`\<`extendShape`\<`Omit`\<\{ `emailAddress`: `ZodTypeAny`; `isEmailAddressVerified`: `ZodTypeAny`; `name`: `ZodTypeAny`; `passwordHash`: `ZodTypeAny`; `role`: `ZodTypeAny`; \}, `"id"` \| `"createdAt"` \| `"name"` \| `"avatarMimeType"` \| `"avatarName"` \| `"creatorId"` \| `"emailAddress"` \| `"isEmailAddressVerified"` \| `"passwordHash"` \| `"role"` \| `"updatedAt"` \| `"updaterId"`\>, \{ `avatar`: `ZodOptional`\<`ZodNullable`\<`ZodType`\<`Promise`\<`FileUpload`\>, `Promise`\<`FileUpload`\>\>\>\>; `emailAddress`: `ZodOptional`\<`ZodTypeAny`\>; `name`: `ZodOptional`\<`ZodTypeAny`\>; `password`: `ZodOptional`\<`ZodString`\>; \}\>, `"strip"`, \{ `avatar`: `Promise`\<`FileUpload`\>; `emailAddress`: `any`; `name`: `any`; `password`: `string`; \}, \{ `avatar`: `Promise`\<`FileUpload`\>; `emailAddress`: `any`; `name`: `any`; `password`: `string`; \}\>, \{ `avatar`: `Promise`\<`FileUpload`\>; `emailAddress`: `any`; `name`: `any`; `password`: `string`; \}, \{ `avatar`: `Promise`\<`FileUpload`\>; `emailAddress`: `any`; `name`: `any`; `password`: `string`; \}\>

Defined in: [src/graphql/inputs/MutationUpdateCurrentUserInput.ts:12](https://github.com/PalisadoesFoundation/talawa-api/blob/31af62eb801979353402f1e291e74768cd64d85c/src/graphql/inputs/MutationUpdateCurrentUserInput.ts#L12)
