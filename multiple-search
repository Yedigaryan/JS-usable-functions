sortedItems = [];          
this.sortedItems = this.items.filter((item: NotesItemInterface) => {
                return searchableString.toLowerCase()
                    .trim()
                    .split(' ')
                    .some((searchable: string) => {
                        return item.label.toLowerCase()
                            .split(' ')
                            .some((item: string) => item.includes(searchable));
                    })
            })
