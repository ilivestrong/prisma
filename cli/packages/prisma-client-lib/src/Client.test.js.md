# Snapshot report for `dist/Client.test.js`

The actual snapshot is saved in `Client.test.js.snap`.

Generated by [AVA](https://ava.li).

## automatic non-scalar sub selection

> Snapshot 1

    `{␊
      users {␊
        __typename␊
      }␊
    }␊
    `

## automatic non-scalar sub selection and enums

> Snapshot 1

    `{␊
      user {␊
        type␊
      }␊
    }␊
    `

## automatic non-scalar sub selection and scalars

> Snapshot 1

    `{␊
      user {␊
        name␊
      }␊
    }␊
    `

## automatic non-scalar sub selection for a connection with scalars

> Snapshot 1

    `{␊
      housesConnection {␊
        pageInfo {␊
          hasNextPage␊
          hasPreviousPage␊
          startCursor␊
          endCursor␊
        }␊
        edges {␊
          node {␊
            id␊
            name␊
          }␊
          cursor␊
        }␊
      }␊
    }␊
    `

## automatic non-scalar sub selection for a connection without scalars

> Snapshot 1

    `{␊
      usersConnection {␊
        __typename␊
      }␊
    }␊
    `

## automatic non-scalar sub selection for relation

> Snapshot 1

    `query ($where: HouseWhereInput) {␊
      house(where: $where) {␊
        user {␊
          __typename␊
        }␊
      }␊
    }␊
    `

## deep related type

> Snapshot 1

    `{␊
      user {␊
        posts {␊
          content␊
        }␊
      }␊
    }␊
    `

## embedded type

> Snapshot 1

    `{␊
      user {␊
        id␊
        posts {␊
          content␊
        }␊
      }␊
    }␊
    `

## nested args

> Snapshot 1

    `query ($where: PostInput!) {␊
      post(where: $where) {␊
        id␊
        title␊
        content␊
      }␊
    }␊
    `

## nested mbedded type

> Snapshot 1

    `{␊
      user {␊
        id␊
        posts {␊
          content␊
          meta {␊
            meta␊
          }␊
        }␊
      }␊
    }␊
    `

## related type

> Snapshot 1

    `{␊
      user {␊
        id␊
      }␊
    }␊
    `

## top level args

> Snapshot 1

    `query ($where: PostInput!) {␊
      post(where: $where) {␊
        id␊
        title␊
        content␊
      }␊
    }␊
    `

## unpacking extract payload - array

> Snapshot 1

    '[{"id":"1","name":"Alice"},{"id":"2","name":"Bob"}]'

## unpacking extract payload - nested array

> Snapshot 1

    '[{"id":"1","name":"My House"},{"id":"2","name":"Summer House"}]'

## unpacking extract payload - nested object

> Snapshot 1

    '{"id":"1","name":"My House"}'

## unpacking extract payload - null from server

> Snapshot 1

    'null'
