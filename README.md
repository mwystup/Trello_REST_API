# 🏆 Trello REST API testing [Postman]

By testing Trello API, we can check how the interaction with the Trello application works. I conducted these tests based on [Trello API documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/). I grouped the tests into several sets: <i> •  board •  list •  card •  checklist •  checkitem •  delete. </i>

* technologies: REST API
* tools: Postman
* methods: create, get, update, delete

✔️ [test screenshots on Google Drive](https://drive.google.com/drive/folders/1BWqutdrAeGkVVaAmwRAnqMxxraWnwx99?usp=sharing)

## :sparkles: Test scope:
- ☑️ [**Board**](#board)
  - [Create a Board](#create_a_board)
  - [Get Boards](#get_boards)
  - [Get a Board](#get_a_board)
  - [Update a Board](#update_a_board)
- ☑️ [**List**](#list)
  - [Create a List on a Board](#create_a_list_on_a_board)
  - [Get Lists on a Board](#get_lists_on_a_board)
  - [Get a List](#get_a_list)
  - [Update a List](#update_a_list)
- ☑️ [**Card**](#card)
  - [Create a new Card](#create_a_new_card)
  - [Get Cards on a Board](#get_cards_on_a_board)
  - [Get a Card on a Board](#get_a_card_on_a_board)
  - [Update a Card](#update_a_card)
- ☑️ [**Checklist**](#checklist)
  - [Create a Checklist on a Card](#create_checklist_on_a_card)
  - [Get Checklists on a Card](#get_checklists_on_a_card)
- ☑️ [**CheckItem**](#checkitem)
  - [Create checkItem on Checklist](#create_checkitem_on_checklist)
  - [Get checkItems on a Checklist](#get_checkitems_on_a_checklist)
  - [Update a checkItem on a Card](#update_a_checkitem_on_a_card)
- ☑️ [**Delete**](#delete)
  - [Delete checkItem on a Card](#delete_checkitem_on_a_card)
  - [Delete a Checklist on a Card](#delete_a_checklist_on_a_card)
  - [Delete a Card](#delete_a_card)
  - [Delete a Board](#delete_a_board)

## :sparkles: Screenshots:

### <a id="board"> ☑️ Board </a>
* <a id="create_a_board"><b> Board </b> - Create a Board </a>
![Create a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/1.%20Create%20a%20Board.jpg)

* <a id="get_boards"><b> Board </b> - Get Boards </a>
![Get Boards](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/2.%20Get%20Boards.jpg)

* <a id="get_a_board"><b> Board </b> - Get a Board </a>
![Get a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/3.%20Get%20a%20Board.jpg)

* <a id="update_a_board"><b> Board </b> - Update a Board </a>
![Update a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/4.%20Update%20a%20Board.jpg)
_______________
### <a id="list"> ☑️ List </a>
* <a id="create_a_list_on_a_board"><b> List </b> - Create a List on a Board </a>
![Create a List on a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/5.%20Create%20a%20List%20on%20a%20Board.jpg)

* <a id="get_lists_on_a_board"><b> List </b> - Get Lists on a Board </a>
![Get Lists on a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/6.%20Get%20Lists%20on%20a%20Board.jpg)

* <a id="get_a_list"><b> List </b> - Get a List </a>
![Get a List](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/7.%20Get%20a%20List.jpg)

* <a id="update_a_list"><b> List </b> - Update a List </a>
![Update a List](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/8.%20Update%20a%20List.jpg)
_______________
### <a id="card"> ☑️ Card </a>
* <a id="create_a_new_card"><b> Card </b> - Create a new Card </a>
![Create a new Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/9.%20Create%20a%20new%20Card.jpg)

* <a id="get_cards_on_a_board"><b> Card </b> - Get Cards on a Board </a>
![Get Cards on a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/10.%20Get%20Cards%20on%20a%20Board.jpg)

* <a id="get_a_card_on_a_board"><b> Card </b> - Get a Card on a Board </a>
![Get a Card on a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/11.%20Get%20a%20Card%20on%20a%20Board.jpg)

* <a id="update_a_card"><b> Card </b> - Update a Card </a>
![Update a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/12.%20Update%20a%20Card.jpg)
_______________
### <a id="checklist"> ☑️ Checklist </a>
* <a id="create_checklist_on_a_card"><b> Checklist </b> - Create Checklist on a Card </a>
![Create Checklist on a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/13.%20Create%20Checklist%20on%20a%20Card.jpg)

* <a id="get_checklists_on_a_card"><b> Checklist </b> - Get Checklists on a Card </a>
![Get Checklists on a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/14.%20Get%20Checklists%20on%20a%20Card.jpg)
_______________
### <a id="checkitem"> ☑️ CheckItem </a>
* <a id="create_checkitem_on_checklist"><b> CheckItem </b> - Create checkItem on Checklist </a>
![Create checkItem on Checklist](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/15.%20Create%20checkItem%20on%20Checklist.jpg)

* <a id="get_checkitems_on_a_checklist"><b> CheckItem </b> - Get checkItems on a Checklist </a>
![Get checkItems on a Checklist](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/16.%20Get%20checkItems%20on%20a%20Checklist.jpg)

* <a id="update_a_checkitem_on_a_card"><b> CheckItem </b> - Update a checkItem on a Card </a>
![Update a checkItem on a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/17.%20Update%20a%20checkItem%20on%20a%20Card.jpg)
_______________
### <a id="delete"> ☑️ Delete </a>
* <a id="delete_checkitem_on_a_card"><b> Delete </b> - Delete checkItem on a Card </a>
![Delete checkItem on a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/18.%20Delete%20checkItem%20on%20a%20Card.jpg)

* <a id="delete_a_checklist_on_a_card"><b> Delete </b> - Delete a Checklist on a Card </a>
![Delete a Checklist on a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/19.%20Delete%20a%20Checklist%20on%20a%20Card.jpg)

* <a id="delete_a_card"><b> Delete </b> - Delete a Card </a>
![Delete a Card](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/20.%20Delete%20a%20Card.jpg)

* <a id="delete_a_board"><b> Delete </b> - Delete a Board </a>
![Delete a Board](https://raw.githubusercontent.com/Caounee/Trello_REST_API/images/21.%20Delete%20a%20Board.jpg)
