# Express

## Start Server

```
npm run start
```

# Mongoose

## schema

```javascript
postSchema = {
  name: {
    type: String,
    required: [true, '名稱必填'],
  },
  tags: {
    type: ['String'],
  },
  type: {
    type: String,
  },
  image: String,
  createdAt: {
    type: Date,
    default: Date.now,
    select: false,
  },
  content: {
    type: String,
    required: [true, '貼文內容必填'],
  },
  likes: Number,
  comments: Number,
};
```

# MongoDB

##
