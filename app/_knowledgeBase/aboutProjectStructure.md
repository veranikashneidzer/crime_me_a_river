## Project structure

**App** folder is an App Router which has next structure:

* `_knowledgeBase` - hidden folder with description for app folder;
* `content` - route group for content pages. Consists of:
  * `books` - page with library of books;
  * `games` - page with games collection;
  * `movies` - page with different types of video content such as movies, series, tv and etc;
  * `news` - page with latest news around the world;
* `general` - route group for the general site pages;
* `page.tsx` - main page of the application;
* `layout.tsx` - main layout for all pages (main page and nested pages);
* `constants.ts` - consists of all constants which are used in the app folder.

Also, there is an [online schema](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=app_routes.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%22hAm6IBLFMkj6_XQiMa60%22%3E7Vttc6o4FP41zt390A4QQf1Y7MvdGbvTvZ07t7tfdlJJJSsQb4hV%2B%2Bv3BBIQidZ6FfvmOJacHGLynOc8kCNtoX48v%2BJ4El6zgEQtxwrmLXTecpxuz4FPaVjkBs9FuWHEaZCb7NJwS5%2BIMlrKOqUBSSuOgrFI0EnVOGRJQoaiYsOcs1nV7YFF1W%2Bd4BGpGW6HOKpbf9BAhGpZTqe0fyV0FOpvtr1e3hNj7axWkoY4YLMlE7pooT5nTORH8bxPIomdxiU%2F73JNbzExThKxzQnXg3%2FCx%2FHdv1%2Fvfvz86y548v8Yd05sNcwjjqZqxWq2YqEh4GyaBESOYrWQPwupILcTPJS9M4g52EIRR9Cy4TDAaZj56sYNFoLwJLM4Vhus9YnrSRAuyHzJpBZyRVhMBF%2BAi%2Br1FKaKVEg1Z2WECgKFS9FBrjJixYpRMXIJHBwo7F6Co7VnHFPB2Zj0WcQ4WCK5hpMA8%2FFvLVht9mo5MFV0edmD1%2B%2F7gbVbhdV267jangHXAuy944oMsHqRkFjZFXS9n1OZSH6M%2BYgmJ4IBnmfgYU3mGTa6H45G8u81polOfzUiTFAOmvdr40QbvqfgaH0Bpy%2BZBsEHJ3gYykZI6kNNypFWeADBENVgm7jAIGwPUSYYIQ0CAhnkVxm0%2F4B3DPHuGuLdOVS427Vw91ki5Poc6%2Fu3QVrDMp3ROMIJtPwH8LxVPRKeYUijYIAXbCpnnQo8HOuWHzJOn8Afl%2BmGuVBXH2RVPG7lmWpMTlLwudGQ2yumazyvOA5wKvRsWBThSUrvs%2FnZBVN9JgSL96Kt9n44YVsrKtAzsMIxsMI%2BmLq6BhW4vGdsXCeESq6qfCYsZwiNohUTBmWV%2BEXkQZ4mUaJw8T9T5hgyT47spxAUmowGmdt5u7R8U%2Btvr0nZCaOJyPBwfXhL1bZO3ZZ7LuXb9e2yDW%2FpzgVQHqYP%2BiTHJUChGZE0guwXWOD7guDPsKVOhY0p9zw%2F1l9sjXRAh2KDZ2LDCMfkkw3Ns8E7Nhs6JjbE7JF%2B0uEIdNj2WnEwOvRMdEjI7JMMzZOhiPzR2NCtsQFP4Mb8MspuBE9FOt%2Fx7nxbNlTv2OUtasNbut4WWzq3yZDYzpqYyP1T%2BhFC0qmGxFS8sBqNSH3XVQvBK6wBIWc3HO32wYA07VP2Uq3w873OTuWKbJ%2F0jmoWqF2N%2B9GLFnZ9Q5IrmtqhfhxlQ%2BjZlCyqCc1Im2l38PakrdCxI2pb%2FVZqT9p2le%2Fcd9K2bNf%2FjrXNaR9d3OobqlzcVMHl44qbKSmbVTetEm9c3ZDhCt6wuhWL2P%2FvTKoStZO85WWsd6xvbfvY%2BqZTpqZvuoT4cQXOlJcNC5zp59%2B3J3Cu4SretMCZ9vh7Ebg%2Fs9rqTvImy7LvWNzc7tHFrV6QyMUtL4h%2FXGkzZWTD0ubVMCfBiOgHGBgXIRuxBEcXpXUFx9JnwGSWZmH6jwixUA8y4ClkViWIZE7F3dLx33KoU1e1zvXTC1ljoRsJrPduubF0lmyWp2WtxYvC3O%2FL441hTtmUD8kGLBXLBSgW2fQDhi50SqA3soaTCAv6SCrTMFEgO%2FWMc7xYclA%2F5JQj30hDScbVmryD3GU6PeuvH9Ao6ZfPoCRjsZRf4GfnvfNzd7552%2FKt8zr55r2Mb%2Fr6dFi%2BdT%2F5tg6bzpZ807edR%2BYbWnmAzOlt5tuqf7vdBN96n3xbh01vW76hV8G3Vb1Czsv0zbN%2FiW%2FQLB%2Fiz93L%2F4RAF%2F8D%3C%2Fdiagram%3E%3C%2Fmxfile%3E) with an actual app routes.