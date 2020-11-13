# django-react-intro
Django/React Introduction


# Wishlist

## Overview

---

### Phase 0

- Go through [django tutorial](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)

### Phase 1

- Django app running on localhost
- Basic bootstrap with django templates on frontend

### Phase 2

- Search for an item using 3rd party APIs

### Phase 3

- APIs created in DRF

### Phase 4

- React frontend connected to APIs

### Phase 5

- Deploy apps to server

### Extras

- email invites
- sign up email verification

---

## Phase 1

Create django application for gift idea sharing between users of the
application. User can create group(s), invite other users to their group
etc.

Member of the group can share his/hers wishlist for some occasion
(Christmas, birthday...), members can see wishlists of other members
of the group and they can select present(s) they want to buy. User
can not see who is buying him which present.

Present have multiple states - *free, reserved, purchased*.

### Views

- User registration / user login
- List view of all groups
- Group create form view
- Detail of the group (list of wished presents of all members of the
group)
- View where user can see all the presents from all groups that he has
reserved / purchased.
